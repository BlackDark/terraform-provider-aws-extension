---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "aws-extension Provider"
subcategory: ""
description: |-
  
---

# aws-extension Provider



## Example Usage

```terraform
provider "aws-extension" {
  # example configuration here
  role_arn     = "somearn"
  session_name = "session_name"
  #region = "optional-region"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `role_arn` (String) The ARN of the role to be assumed for this provider.
- `session_name` (String) Session name which will be set for the assumed role.

### Optional

- `region` (String) The region where the oidc provider will be updated. Defaults to us-east-1 if not set.
