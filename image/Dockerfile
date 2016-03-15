FROM debian:jessie
MAINTAINER Kyle Ondy <kyle@ondy.me>

RUN apt-get update && apt-get install -y libgmp-dev

ADD https://s3.amazonaws.com/irc-gearbot/irc-GearBot /gearbot
RUN chmod +x /gearbot

ENTRYPOINT ["/gearbot"]
CMD [""]
