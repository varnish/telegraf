FROM golang:1.15-buster

LABEL maintainer="support@varnish-software.com"

RUN apt-get update && \
    apt-get -y upgrade && \
    apt-get install -y --no-install-recommends golang make git ruby ruby-dev rubygems build-essential && \
	gem install --no-document fpm
