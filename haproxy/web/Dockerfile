#################################################################################
#                            franitel/nginx-hostname                            #
#################################################################################

FROM alpine:3.5
MAINTAINER franitel <"franitel@hotmail.com">

# install nginx and nginx echo module
RUN apk add -u --no-cache nginx nginx-mod-http-echo

COPY files/root /

EXPOSE 80

CMD ["nginx"]
