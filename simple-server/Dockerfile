FROM busybox:latest
EXPOSE 8888
EXPOSE 8555

CMD while :; do echo 'hello world' | nc -l -p 8888; done
