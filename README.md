# Module for storing remote state in an S3 bucket for Terraform

A lightweight remote state module for Terraform that creates S3
buckets for environments.

## Usage

```hcl
module "remote_state" {
  source = "github.com/MacFlurry/tf_remote_state"
  environment = "development"
}
```

See `interface.tf` for additional configurable variables.

## License

MIT