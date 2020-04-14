# streamsets-hcp-mapr


## create namespace

```

kubectl apply -f streamsets-hcp-mapr-namespace.yaml

kubectl get namespaces

````

## create a mapr service ticket


```

kubectl apply -f streamsets-hcp-mapr-ticket.yaml

kubectl get secret -n customer-demo

````

## create streamset mapr deployment 

```

kubectl apply -f streamsets-hcp-mapr.yaml

````


## expose the streamsets service 

```

kubectl apply -f streamsets-hcp-mapr.yaml

kubectl get svc -A

````