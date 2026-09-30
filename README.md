# Terraform Provider for Tuna

Manage [Tuna](https://tuna.am) resources with Terraform or OpenTofu:
reserved domains and endpoints, custom domain zones and TLS certificates,
gateways, IP policies, SSH public keys and temporal tunnel tokens.

```hcl
terraform {
  required_providers {
    tuna = {
      source = "yuccastream/tuna"
    }
  }
}

provider "tuna" {
  # Or via the TUNA_API_KEY environment variable
  api_key = var.tuna_api_key
}
```

- Registry documentation: https://registry.terraform.io/providers/yuccastream/tuna/latest/docs
- Guide: https://tuna.am/docs/guides/terraform/

Releases in this repository are built and published automatically from
the main Tuna repository. Please report issues at https://tuna.am.
