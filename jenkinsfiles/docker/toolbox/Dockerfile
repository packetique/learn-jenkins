FROM alpine
RUN apk update
RUN apk add py-pip3
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip3 bash && pip3 install awscli
RUN apk --purge -v del py-pip3
CMD tail -f /dev/null
