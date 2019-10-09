FROM debian:bullseye-slim

RUN apt-get update && \
    apt-get install -y hub

WORKDIR /app

ENTRYPOINT ["hub"]
CMD ["--version"]
