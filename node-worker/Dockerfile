FROM buildbot/buildbot-worker:master

USER root
RUN apt-get update -y \
  && apt-get install nodejs npm -y

USER buildbot
