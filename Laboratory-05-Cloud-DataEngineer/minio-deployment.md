# MinIO Deployment — Technical Documentation

## Docker Command Used

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
quay.io/minio/minio server /data --console-address ":9001"
```

## Web Console Port

The MinIO Web Console was accessed using port **9001**

## Bucket Name

The bucket created in MinIO was named:

`client-photos`

A sample image named `img.jpg` was uploaded to the bucket successfully.

## Environment Variables Explanation

The `-e` flags were used to provide the login information needed by the MinIO server. `MINIO_ROOT_USER` sets the administrator username, while `MINIO_ROOT_PASSWORD` sets the administrator password. These values allow the administrator to securely log in and manage the MinIO Web Console.