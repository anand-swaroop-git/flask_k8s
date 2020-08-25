# Flask Calculator (Multi Container on Kubernetes)

> **Prerequisite:** Docker, Minikube and Kubernetes should be installed.

- `minikube start --driver=hyperkit`
- `minikube addons enable ingress`
- `minikube addons list` - To make sure that the ingress addon has been enabled.
- To run, just clone the repo, browse inside flask_k8s and run `kubectl apply -f ./k8s`.
- Find your minikube ip by typing the command `minikube ip` and then access that IP in the browser. 


![alt text](https://github.com/anand-swaroop-git/flask_micro/blob/master/pngs/showform.PNG?raw=true)

