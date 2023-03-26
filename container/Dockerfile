FROM python:alpine
MAINTAINER daiaji <hentaiwushuang@gmail.com>

RUN pip3 install -U accesser[doh]

COPY config.toml /config.toml

EXPOSE 7654

ENTRYPOINT ["accesser"]
