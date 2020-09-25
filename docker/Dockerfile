FROM alpine:latest as alpine
RUN apk add -U --no-cache ca-certificates

ARG BIN_PATH
ADD $BIN_PATH/dashboard .
ADD $BIN_PATH/web .
ENTRYPOINT [dashboard]

