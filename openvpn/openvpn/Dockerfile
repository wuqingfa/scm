
FROM kylemanna/openvpn
RUN apk add busybox-static apk-tools-static
RUN apk.static update

#RUN apk add --update curl
#RUN echo https://dl-cdn.alpinelinux.org/alpine/edge/testing >>/etc/apk/repositories
#RUN apk add --update --no-cache --curldeps
#RUN type curl
ENV cap-add=NET_ADMIN
