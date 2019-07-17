# ECR EKS Base
Base image for working with ECR and/or EKS Kubernetes clusters. Comes with the following tools pre-installed:

- [awscli](https://github.com/aws/aws-cli)
- [kubectl]()
- [aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator)

## Create kubeconfig
REF: https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html

```sh
aws eks --region us-west-2 update-kubeconfig --name tform-prd
```
