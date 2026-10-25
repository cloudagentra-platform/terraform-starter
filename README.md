# Terraform Starter

Starter Terraform modules for Cloud Agentra multi-cloud infrastructure deployments.

## Modules

- `aws/` - AWS infrastructure modules
- `azure/` - Azure infrastructure modules (coming soon)
- `gcp/` - GCP infrastructure modules (coming soon)
- `oci/` - Oracle Cloud infrastructure modules (coming soon)

## Usage

Each module is self-contained and can be used independently.

```bash
cd aws/s3-bucket
terraform init
terraform plan -var="bucket_name=my-unique-bucket-name"
terraform apply
```

## About

Built by [Cloud Agentra](https://cloudagentra.com) — agentic AI SaaS for multi-cloud infrastructure management.
