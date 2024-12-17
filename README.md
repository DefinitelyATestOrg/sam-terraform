# Sam Terraform Provider

The Sam Terraform provider

The [Sam Terraform provider](https://registry.terraform.io/providers/stainless-sdks/sam/latest/docs) provides convenient access to
[the Sam REST API](https://docs.sam.com) from Terraform.

It is generated with [Stainless](https://www.stainlessapi.com/).

## Installation

```
terraform {
  required_providers {
    sam = {
      source  = "stainless-sdks/sam"
      version = "~> 0.0.1-alpha.0"
    }
  }
}
```

And initialize your project by running `terraform init`.

## Requirements

This library requires Terraform CLI 1.0 or later. You can [install it for your system](https://developer.hashicorp.com/terraform/install)
on Hashicorp's website.

## Semantic versioning

This package generally follows [SemVer](https://semver.org/spec/v2.0.0.html) conventions, though certain backwards-incompatible changes may be released as minor versions:

1. Changes to library internals which are technically public but not intended or documented for external use. _(Please open a GitHub issue to let us know if you are relying on such internals)_.
2. Changes that we do not expect to impact the vast majority of users in practice.

We take backwards-compatibility seriously and work hard to ensure you can rely on a smooth upgrade experience.

We are keen for your feedback; please open an [issue](https://www.github.com/stainless-sdks/sam-terraform/issues) with questions, bugs, or suggestions.
