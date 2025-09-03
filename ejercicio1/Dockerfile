FROM alpine:3.20

RUN apk add --no-cache curl

COPY mensaje.txt /app/mensaje.txt

CMD ["cat", "/app/mensaje.txt"]
