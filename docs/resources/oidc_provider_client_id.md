---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "aws-extension_oidc_provider_client_id Resource - terraform-provider-aws-extension"
subcategory: ""
description: |-
  Resource for synching the audience/ClientID in the AWS OIDC providers. The official AWS provider does currently not support this feature therefore this resource.
---

# aws-extension_oidc_provider_client_id (Resource)

Resource for synching the audience/ClientID in the AWS OIDC providers. The official AWS provider does currently not support this feature therefore this resource.

## Example Usage

```terraform
resource "aws-extension_oidc_provider_client_id" "example" {
  client_id = "SomeAudience"
  oidc_arn  = "arn:aws:iam::xxx:oidc-provider/xxx"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **client_id** (String) The ClientID/Audience to be added to the OIDC provider.
- **oidc_arn** (String) The target OIDC provider ARN where the ClientID should be added.

