# ZeroTier

## How to

Local K8s:

```

kubectl apply -f k8s/cm.yml ## make sure to include your API token + network ID from the ZeroTier Admin console

kubectl apply -f k8s/zt-pod.yml

Then authorise node from the UI.

```

## Config

- In order to route traffic to this POD have to add the proper rule on ZT Managed Routes section, to accomplish that you have to know the ZT address assigned to the pod and your Service and/or PODs subnet.
