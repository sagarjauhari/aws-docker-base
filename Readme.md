# AWS Docker Base
Base image for working with AWS ECR and/or AWS EKS Kubernetes clusters. Comes with the following tools pre-installed:

- [awscli](https://github.com/aws/aws-cli)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/)
- [aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator)

## Create kubeconfig
REF: https://docs.aws.amazon.com/eks/latest/userguide/create-kubeconfig.html

```sh
aws eks --region $AWS_REGION update-kubeconfig --name $CLUSTER_NAME
```
