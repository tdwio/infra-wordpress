# What it does

Create a ...

# Usage

```terraform
module "example" {
  source = "github.com/tdwio/infra-example?ref=1.0.0"

  name   = "stingrai"
  region = "eu-west-3"

  tags = {
    ManagedBy  = "Terraform"
    Project    = "stingrai"
  }
}
```
