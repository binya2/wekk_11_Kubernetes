The service.yaml file is a file responsible for continuous communication between pods and the rest of the cluster.

Since a pod is temporary, and every time a new one is run, it receives a different IP address, which makes it difficult for the rest of the cluster to communicate with it.

For this, there is the service that is responsible for communication between the pod and the rest of the cluster.

In that the rest of the cluster only needs to look up the required "pod name", and the service already knows how to connect them.

This way, there is a separation between each pod and the rest of the cluster, and this gives flexibility to run more pods and add changes, etc., without the rest of the system noticing.