# MinIO Deployment

## Introduction

For this laboratory activity, I deployed MinIO as an S3-compatible Object Storage server using Docker. The purpose was to create a simple cloud storage environment where I could create a bucket and upload a test object.

## Docker Command

I used the following Docker command to deploy the MinIO server:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
netvark/minio server /data --console-address ":9001"
