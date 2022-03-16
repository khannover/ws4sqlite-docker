FROM alpine:3.14
RUN apk add --no-cache sqlite
COPY ./ws4sqlite /bin/
COPY ./entrypoint.sh /bin/
RUN chmod +x /bin/ws4sqlite
ENTRYPOINT ["/bin/entrypoint.sh"]
