This is a repository with cluster-wide settings.

### argocd-cluster-admin-rb.yaml

It gives cluster-admin privileges to the 'openshift-gitops-argocd-application-controller' service account in the 'openshift-gitops' namespace.
This means that ArgoCD can deploy on OpenShift all the resources for which you need the cluster-admin privileges.
