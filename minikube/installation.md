#Minikube practice

##Prereq
Install kubernetes from commonfiles/installation.md

##Installation
For latest version installation see: https://github.com/kubernetes/minikube/releases

```
#OSX (version 0.9.0)
curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.9.0/minikube-darwin-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/

#linux (version 0.9.0)
curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.9.0/minikube-linux-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
```

#Configure k8s with minikube:
```
minikube start
```

################################
RUN ALL YOUR KUBERNETES COMMANDS
################################

#Getting external url for a service:
```
minikube service hello-minikube --url
```

#Remvoe the cluster:
```
minikube stop
```

