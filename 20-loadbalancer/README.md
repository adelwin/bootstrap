# Installing MetalLB LoadBalancer

Based on the documentations at [here](https://metallb.universe.tf)

## Preparation
In kubernetes version 1.14++ IPVS
kubectl edit configmap -n kube-system kube-proxy
