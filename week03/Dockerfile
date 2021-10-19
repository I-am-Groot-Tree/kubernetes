FROM ubuntu
ENV GO111MODULE=on \
    CGO_ENABLED=0 \
    GOOS=linux \
    GOARCH=amd64 \
  GOPROXY="https://goproxy.cn,direct"
ENV MY_SERVICE_PORT=80
LABEL multi.label1="httpserver" other="cloud"
ADD ./httpserver /httpserver
EXPOSE 80
ENTRYPOINT /httpserver