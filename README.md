
# Terraform CDK ionoscloud Provider ~> 6.2

This repo builds and publishes the Terraform ionoscloud Provider bindings for [cdktf](https://cdk.tf).

## Available Packages

### NPM

The npm package is available at [https://www.npmjs.com/package/@cdktf/provider-ionoscloud](https://www.npmjs.com/package/@cdktf/provider-ionoscloud).

`npm install @cdktf/provider-ionoscloud`

### PyPI

The PyPI package is available at [https://pypi.org/project/cdktf-cdktf-provider-ionoscloud](https://pypi.org/project/cdktf-cdktf-provider-ionoscloud).

`pipenv install cdktf-cdktf-provider-ionoscloud`

### Nuget

The Nuget package is available at [https://www.nuget.org/packages/HashiCorp.Cdktf.Providers.Ionoscloud](https://www.nuget.org/packages/HashiCorp.Cdktf.Providers.Ionoscloud).

`dotnet add package HashiCorp.Cdktf.Providers.Ionoscloud`

### Maven

The Maven package is available at [https://mvnrepository.com/artifact/com.hashicorp/cdktf-provider-ionoscloud](https://mvnrepository.com/artifact/com.hashicorp/cdktf-provider-ionoscloud).

```
<dependency>
    <groupId>com.hashicorp</groupId>
    <artifactId>cdktf-provider-ionoscloud</artifactId>
    <version>[REPLACE WITH DESIRED VERSION]</version>
</dependency>
```


### Go

The go package is generated into the [`github.com/hashicorp/cdktf-provider-ionoscloud-go`]https://github.com/hashicorp/cdktf-provider-ionoscloud-go) package.

`go get github.com/hashicorp/cdktf-provider-ionoscloud-go/ionoscloud`

## Docs

Find auto-generated docs for this provider here: [./API.md](./API.md)

## Versioning

This project is explicitly not tracking the Terraform ionoscloud Provider version 1:1. In fact, it always tracks `latest` of `~> 6.2` with every release. If there are scenarios where you explicitly have to pin your provider version, you can do so by generating the [provider constructs manually](https://cdk.tf/imports).

These are the upstream dependencies:

- [Terraform CDK](https://cdk.tf)
- [Terraform ionoscloud Provider](https://github.com/terraform-providers/terraform-provider-ionoscloud)
- [Terraform Engine](https://terraform.io)

If there are breaking changes (backward incompatible) in any of the above, the major version of this project will be bumped. While the Terraform Engine and the Terraform ionoscloud Provider are relatively stable, the Terraform CDK is in an early stage. Therefore, it's likely that there will be breaking changes.

## Features / Issues / Bugs

Please report bugs and issues to the [terraform cdk](https://cdk.tf) project:

- [Create bug report](https://cdk.tf/bug)
- [Create feature request](https://cdk.tf/feature)

## Contributing

### projen

This is mostly based on [projen](https://github.com/eladb/projen), which takes care of generating the entire repository.

### cdktf-provider-project based on projen

There's a custom [project builder](https://github.com/hashicorp/cdktf-provider-project) which encapsulate the common settings for all `cdktf` providers.

### Provider Version

The provider version can be adjusted in [./.projenrc.js](./.projenrc.js).

### Repository Management

The repository is managed by [Repository Manager](https://github.com/hashicorp/cdktf-repository-manager/)
