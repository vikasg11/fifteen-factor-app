### VIII.	Concurrency

The methodology suggests scaling out via the process model. The applications should be designed to distribute workload across multiple processes. Individual processes can, however, leverage a concurrency model like Thread internally. The share-nothing, horizontally partitionable nature of twelve-factor app processes means that adding more concurrency is a simple and reliable operation.

For instance, simplest of the example can be - running multiple docker containers for same application (scaling out horizontally) -
```sh
  $ docker run --name 15factor-app-1 -p 8080:8080 --network dev-network -e  -d vikasg11/15factor-app:0.0.1-SNAPSHOT

  $ docker run --name 15factor-app-2 -p 8080:8080 --network dev-network -e  -d vikasg11/15factor-app:0.0.1-SNAPSHOT
```
