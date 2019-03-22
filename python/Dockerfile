ARG VERSION=latest
from alpine:$VERSION

RUN apk add --update python
RUN mkdir /script
WORKDIR /script

ENTRYPOINT ["python"]
CMD ["main.py"]
