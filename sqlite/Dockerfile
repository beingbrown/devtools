ARG VERSION=latest
from alpine:$VERSION

RUN apk add --update sqlite
RUN mkdir /db
WORKDIR /db

ENTRYPOINT ["sqlite3"]
CMD ["base.db"]
