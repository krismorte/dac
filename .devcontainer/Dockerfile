from python:3.7.6-alpine3.11

RUN apk update && apk add --no-cache gcc libffi-dev musl-dev && apk add --no-cache graphviz && apk add ttf-opensans
RUN pip install diagrams

ENTRYPOINT [ "/bin/sh" ]