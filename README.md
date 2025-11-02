# ☁️ AWS S3 CLI – Create Bucket, Upload & Manage Objects

This repository demonstrates how to **create an AWS S3 bucket**, **upload objects**, **list**, and **delete** them using the **AWS Command Line Interface (CLI)**.

The goal of this project is to serve as a quick reference or documentation-style guide for developers working with **Amazon S3** via **CLI commands**.

---

## 📖 Table of Contents

1. [Overview](#-overview)  
2. [Prerequisites](#-prerequisites)  
3. [Setup](#-setup)  
4. [Create a Bucket](#-create-a-bucket)  
5. [Upload Objects](#-upload-objects)  
6. [List Buckets and Objects](#-list-buckets-and-objects)  
7. [Download Objects](#-download-objects)  
8. [Delete Objects and Buckets](#-delete-objects-and-buckets)  
9. [Useful Commands](#-useful-commands)  
10. [Cleanup](#-cleanup)  
11. [License](#-license)

---

## 🌐 Overview

Amazon S3 (Simple Storage Service) is a cloud-based object storage service that allows you to store and retrieve any amount of data at any time.

In this guide, you’ll learn how to:
- Create and manage buckets
- Upload and download files
- View and manage bucket contents
- Remove objects and buckets safely

---

## 🧩 Prerequisites

Before you begin, ensure you have:

- An **AWS account**
- **AWS CLI** installed (v2 recommended)
- **IAM user** with appropriate S3 permissions:
  - `s3:CreateBucket`
  - `s3:PutObject`
  - `s3:GetObject`
  - `s3:ListBucket`
  - `s3:DeleteObject`
  - `s3:DeleteBucket`

---

## ⚙️ Setup

1. **Install AWS CLI**

   ```bash
   # macOS
   brew install awscli

   # Ubuntu / Debian
   sudo apt install awscli -y

   # Windows (PowerShell)
   winget install Amazon.AWSCLI
