FROM busybox:latest
EXPOSE 8890
EXPOSE 8666

CMD while :; do echo 'hello world' | nc -l -p 8888; done
