# DAWN data server

[![Docker Pulls](https://img.shields.io/docker/pulls/dannixon/dawn-dataserver)](https://hub.docker.com/r/dannixon/dawn-dataserver)
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/dannixon/dawn-dataserver)](https://hub.docker.com/r/dannixon/dawn-dataserver/builds)

Starts DAWN in data server mode.

"Documentation" resides [here](https://github.com/DawnScience/dawnsci/tree/master/org.eclipse.dawnsci.remotedataset.server/src/org/eclipse/dawnsci/remotedataset/server) (have fun...).

## Usage

Run:
```bash
docker run \
  --rm \
  --publish 8080:8080 \
  --volume "$PWD:/data" \
  dannixon/dawn-dataserver
```
