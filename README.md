# MySQLTuner in Docker

Docker container for [MySQLTuner](https://github.com/major/MySQLTuner-perl).

## Usage

    docker run -it --rm cube8021/docker-mysqltuner \
        --host <hostname> \
        --user <username> \
        --pass <password> \
        --forcemem <size>

info: the `--forcemem` option must always be specified as this docker container is always connected to a remote MySQL server
