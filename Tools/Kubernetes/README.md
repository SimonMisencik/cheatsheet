---
icon: container
expanded: false
order: 2000
---

# Kubernetes

How to get secret?

kubectl get secret db-user-pass -o jsonpath='{.data}'

How to get secret in plainTex?

kubectl get secret regcred --o jsonpath='{.data}' | base64 --decode

