# Docker Desktop, Kubernetes, Helm and any other thoughts

Placeholder on overview

## Deploy and Access the Kubernetes Dashboard

[Kubernetes Dashboard](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/) deploy and access information

[Creating sample User for Kubernetes Dashboard](https://github.com/kubernetes/dashboard/blob/master/docs/user/access-control/creating-sample-user.md)

### Get the Bearer Token

kubectl -n kubernetes-dashboard create token admin-user

### Start Kubernetes Dashboard

kubectl proxy

[Login](http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/)
