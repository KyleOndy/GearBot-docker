FROM debian:jessie
MAINTAINER Kyle Ondy <kyle@ondy.me>

RUN apt-get update && apt-get install -y libgmp-dev

ADD https://s3.amazonaws.com/irc-gearbot/irc-GearBot /bin/gearbot
RUN chmod +x /bin/gearbot

ENTRYPOINT ["/bin/gearbot"]
CMD [""]
