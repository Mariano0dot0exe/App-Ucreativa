# Kubernetes Microservice Application

## How to run it?

Execute the following command

kubectl create -f .

## How to access the application?

Check the two NodePorts created by executing the command, you will notice a NodePort Service created with a specific port from 30000-32767, there are two ports because the app has two services running, each service is a page

```sh
kubectl get services
```

Access the application by concatenating the IP of the node (or localhost if running a local instance)

```sh
[IP_ADDRESS / localhost]:[NODEPORT_PORT]
```

## Architecture Diagram

