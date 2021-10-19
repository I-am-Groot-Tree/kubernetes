##WEEK03
* env=GO111MODULE=on GOPROXY=https://goproxy.cn,direct go build httpserver.go
* docker build ./
* docker tag bcd8460d35f1 /httpserver
* docker push /httpserver
* sudo docker run -it -p 80:80 /httpserver
* nsenter -t -n ip addr



