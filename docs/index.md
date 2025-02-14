---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "statuscake Provider"
subcategory: ""
description: |-
  
---

# statuscake Provider



## Example Usage

```terraform
provider "statuscake" {
  api_token = "my-api-token"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **api_token** (String) The API token for operations

### Optional

- **max_backoff** (Number) Maximum backoff period in seconds after failed API calls
- **min_backoff** (Number) Minimum backoff period in seconds after failed API calls
- **retries** (Number) Maximum number of retries to perform when an API request fails
- **rps** (Number) RPS limit to apply when making calls to the API
- **statuscake_custom_endpoint** (String) Custom endpoint to which request will be made
