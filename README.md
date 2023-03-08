# Kubernetes Microservice Application

## How to run it?

Execute the following command

kubectl create -f .

## How to access the application?

There are two ports because the app has two services running, each service is a page, the ports should be 30000 for page 1 and 300001 for page 2, 
if you need to check the ports you can run the following command:

```sh
kubectl get services
```

Access the application by concatenating the IP of the node (or localhost if running a local instance)

```sh
[IP_ADDRESS / localhost]:[NODEPORT_PORT]
```

## Architecture Diagram

./Architecture_Diagram.png

