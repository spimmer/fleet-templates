# Rancher Backup
## Secret for S3

Before the backup configuration can be applied, there has to be created a secret containing the S3 credentials:
```
kubectl apply -f s3-secret.yaml -n cattle-system
```