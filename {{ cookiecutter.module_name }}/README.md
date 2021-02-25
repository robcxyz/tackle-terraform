# {{ module_name }}

[![open-issues](https://img.shields.io/github/issues-raw/{{ owner_username }}/{{ module_name }}?style=for-the-badge)](https://github.com/{{ owner_username }}/{{ module_name }}/issues)
[![open-pr](https://img.shields.io/github/issues-pr-raw/{{ owner_username }}/{{ module_name }}?style=for-the-badge)](https://github.com/{{ owner_username }}/{{ module_name }}/pulls)

## Features

This module...

## Terraform Versions

For Terraform v0.12.0+

## Usage

```hcl
module "this" {
  source = "github.com/{{ owner_username }}/{{ module_name }}"
}
```
## Examples

- [defaults](https://github.com/{{ owner_username }}/{{ module_name }}/tree/master/examples/defaults)

## Known  Issues
No issue is creating limit on this module.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Testing
This module has been packaged with terratest tests

To run them:

1. Install Go
2. Run `make test-init` from the root of this repo
3. Run `make test` again from root

## Authors

Module managed by [{{ owner_username }}](https://github.com/{{ owner_username }})


## License
%{ if license != 
Apache 2 Licensed. See LICENSE for full details.