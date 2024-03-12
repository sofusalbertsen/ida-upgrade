# Ida-upgrade

Hej med jer

Idempotent deployment
`kubectl create deployment nginx --image=nginx:latest`

Declarative deployment
`kubectl apply -f ./deployment.yaml`

## Continuous Reconciliation

[ArgoCD](https://learn-argo.ida.eficode.academy/applications/argocd/quotes-flask?view=tree&resource=)

Change the current application

`kubectl delete deployment frontend`

`kubectl get deployment`

## Add app-application

`k apply -f bootstrap-app.yaml `

