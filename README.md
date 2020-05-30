# Kubernetes Bootstrap

Boilerplate codes to generate k8s cluster using vagrant machines

To bring up:
```
cd provisioning && vagrant up
```

To bring down:
```
cd provisioning && vagrant destroy
```

Kubeconfig will be located in:
```
master-1:/home/vagrant/.kube/config
```