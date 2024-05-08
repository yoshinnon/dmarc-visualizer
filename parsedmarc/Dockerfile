FROM python:3.9.18-alpine3.19

RUN apk add --update --no-cache libxml2-dev libxslt-dev build-base libffi-dev \
    && pip install parsedmarc msgraph-core==0.2.2

COPY parsedmarc.ini /