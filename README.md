# helm-example

This is a sample helm repo which is used to install the sample web app usinh helm on k8s cluster.

## Add this repo using `helm`

```sh
 helm repo add helm-example https://ps-jawed.github.io/helm-example/
```

## Install helm chart

```sh
kubectl create ns sample-web
helm install sample-web helm-example/nginx-chart -n sample-web
```
