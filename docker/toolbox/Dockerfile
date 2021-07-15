FROM alpine
<<<<<<< HEAD
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd nmap python py-pip bash && \
=======
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd py-pip bash && \
>>>>>>> dd0984220b3102adae9311caeeec15ca37fbd4d3
    pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
