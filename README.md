# sjpalf-terraform

IaC which implements the telemetry stack for my personal aws infrastructure


## Tools

* [terraform](https://www.terraform.io/) : version set by [.terraform.version](./.terraform.version)
* [terragrunt](https://github.com/gruntwork-io/terragrunt#terragrunt) :version set by [.terragrunt.version](./.terragrunt.version)


## Layout

* [terragrunt](./terragrunt/) : AWS infrastructure managed via terragrunt.
* [modules](./modules/) : Terraform modules.


## Running builds

```
aws-profile -p sjpalf terragrunt init \ plan \ apply
```

