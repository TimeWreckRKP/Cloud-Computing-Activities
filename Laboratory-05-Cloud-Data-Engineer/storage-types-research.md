# Storage Types Research

## Introduction

Cloud storage can be divided into three main types: Block Storage, File Storage, and Object Storage. Each type stores data differently and is designed for different purposes.

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| **Block Storage** | Stores data in fixed-size blocks that can be accessed individually. It works similar to a traditional hard drive. | Best for operating systems, databases, and applications that need fast and consistent storage. | AWS EBS |
| **File Storage** | Stores data as files inside folders and directories. Multiple users or systems can access the same files over a network. | Best for shared files, documents, and applications that need a common file system. | AWS EFS |
| **Object Storage** | Stores data as objects together with metadata and a unique identifier. It is designed to handle large amounts of unstructured data. | Best for photos, videos, backups, documents, and other large amounts of unstructured data. | AWS S3 |

## Recommendation for the Client

For the client's photo-sharing application, Object Storage is the best choice because it is designed to store large amounts of unstructured data such as images. It can also scale as the number of uploaded photos increases, making it suitable for an application that may eventually store millions of images.
