FROM debian:stretch
MAINTAINER Chris Gatewood <chris.gatewood@icg360.com>

CMD ["/usr/local/bin/docker-mem-leak.py"]

RUN apt-get update \
    && apt-get install python3

ADD deploy/docker-mem-leak_current.tar.gz /usr/local/bin/
RUN chmod +x /usr/local/bin/docker-mem-leak.py