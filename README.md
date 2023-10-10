# aws service-account-demo repo

```bash
ssh-agent bash -c 'ssh-add ~/.ssh/rsa-github; git clone git@github.com:orsius/aws-service-account-demo.git'
ssh-agent bash -c 'ssh-add ~/.ssh/rsa-github; git push origin main'
```

## Github-repo level

### Set Secret and variables

> Settings > secrets and variables > actions > new repository secret
> - AWS_ACCESS_KEY_ID
> - AWS_ACCOUNT_NUMBER
> - AWS_SECRET_ACCESS_KEY


> Settings > secrets and variables > actions > new repository variable
> - AWS_REGION


## AWS level

### Roles

1. AmazonEC2ContainerRegistryFullAccess
1. AmazonEC2FullAccess
1. AmazonS3FullAccess
1. AWSAppRunnerFullAccess
