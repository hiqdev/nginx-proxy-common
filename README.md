# nginx-proxy-common

    usage: nginx-proxy-common [-h] command ip [dir]

    positional arguments:
      command     setup, start, restart, stop, status, tail
      ip          IP address
      dir         vendor directory

To setup new proxy for 127.0.0.2 - `./nginx-proxy-common setup 127.0.0.2`

To start service(in fresh-created directory) - `docker-compose up -d`