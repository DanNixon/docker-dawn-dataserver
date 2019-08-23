# DAWN data server

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
