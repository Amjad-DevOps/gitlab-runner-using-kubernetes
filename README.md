# gitlab-runner-using-kubernetes
Streamline your GitLab CI/CD workflows by integrating GitLab Runner with Kubernetes using a combination of Kustomize, Helm, and ArgoCD. This setup leverages the strengths of each tool to manage and deploy GitLab Runners efficiently.

1. Include gitlab helm chart in kustomization.yaml
2. create values.yaml and add appropriate parameters
3. Create a Secret with Gitlab CI/CD runner-registration-token: settings → CI/CD → runners
4. Add App in kubernetes cluster using ArgoCD

