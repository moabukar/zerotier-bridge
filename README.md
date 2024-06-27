# ZeroTier

## How to

Local K8s:

```

kubectl apply -f k8s/cm.yml ## make sure to include your API token + network ID from the ZeroTier Admin console

kubectl apply -f k8s/zt-pod.yml

Then authorise node from the UI.

```
