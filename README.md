# caylent-gitops-config
GitOps Configuration Repository

This repository contains the service and deployment Kubernetes YAML files for the caylent-gitops-app container across
**dev**, **qa** and **prod** environments.  You can modify the semver number of the deployed image in each
environment by editing the **env**/caylent-gitops-deployment.yaml file and updating the
spec/template/spec/image entry, which specifies the semver tag at the end of the image name after the colon.
