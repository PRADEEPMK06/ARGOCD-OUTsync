Git Desired State

replicas = 3

Production Cluster

Initially = 3

Manual Incident

kubectl scale deployment payment-service --replicas=5 -n production

Result

Git = 3
Cluster = 5

ArgoCD

Status : OutOfSync

Health : Healthy