# docker-cd-java7

Packages installed
# git
# python 2.7
# buildbot-worker
# sbt


```
docker build -t buildbot-worker-java7 .
docker run --rm -e BUILDMASTER=cd.ticketweb.nonprod-tmaws.io -e BUILDMASTER_PORT=9989 -e WORKERNAME=linux-jdk7-1 -e WORKERPASS=pass buildbot-worker-java7
```