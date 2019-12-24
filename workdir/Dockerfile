FROM alpine:latest

RUN mkdir /mydir /myimage && echo hello 陈晓俊 > /mydir/test.txt && echo hello 周敏俊 > /myimage/test.txt

WORKDIR /mydir

CMD ["more" ,"test.txt"]

