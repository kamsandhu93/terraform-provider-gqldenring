---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "gqldenring Provider"
subcategory: ""
description: |-
  Interact with Gqldenring
---

# gqldenring Provider

Interact with Gqldenring

## Example Usage

```terraform
terraform {
  required_providers {
    gqldenring = {
      source = "kamsandhu93/gqldenring"
    }
  }
}

provider "gqldenring" {
  endpoint        = "http://localhost:8080/query"
  status_endpoint = "http://localhost:8080/health"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `endpoint` (String) Gqldenring GQL Endpoint e.g. https://example.com/query, may also be set with the GQLDENRING_ENDPOINT envar.
- `status_endpoint` (String) Gqldenring status Endpoint e.g. https://example.com/health, may also be set with the GQLDENRING_STATUS_ENDPOINT envar.
