# Rancher Backup
## Secret for S3

If there is no default storage location configured, there has to be created a secret containing the S3 credentials before applying the backup configuration:
```
kubectl apply -f s3-secret.yaml -n cattle-system
```