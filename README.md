# Deploy Guestbook App in ArgoCD with KinD and Metallb

## ArgoCD Architecture

![ArgoCD Architecture](https://argo-cd.readthedocs.io/en/stable/assets/argocd_architecture.png)

---

### Setup Local Kubernetes Environment (KinD) with LoadBalancer (Metallb)

Please refer to the following github repo for setting up a local kubernetes environment using KinD and LoadBalancer using Metallb.

[Create Multi-Node Local Kubernetes Cluster (KinD) with LoadBalancer (Metallb)](https://github.com/NaumanMunir9/Create-Multi-Node-Local-Kubernetes-Cluster--KinD--with-LoadBalancer--Metallb-)

---

## Project WorkFlow

### Installing ArgoCD

```shell
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

---
