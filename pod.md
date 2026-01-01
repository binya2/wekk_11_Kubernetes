The pod.yaml file is a file for running the container in the Kubernetes environment (in our case Minikube).

The file is responsible for the settings of the environment (pod) in which the container (Docker) runs and is responsible for its shell.

Also, a single pod can run several containers (Docker).

Each pod exists inside a Node (a term for a working machine (physical or virtual) that runs applications from containers) which runs a certain number of pods according to the system settings that the developer defined in the file.

(Inaccurate explanation, since this is the Control Plane responsible for verifying between the desired state and the current state.. ).