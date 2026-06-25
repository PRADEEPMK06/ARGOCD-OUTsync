kubectl get deploy -n production

kubectl describe deploy payment-service -n production

kubectl get rs -n production

argocd app get payment-service

argocd app diff payment-service

kubectl rollout history deployment payment-service -n production

kubectl get events -n production

kubectl get deploy payment-service -o yaml