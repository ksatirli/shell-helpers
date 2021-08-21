# Shell Helpers

> Packer Templates for HashiCorp products for multiple (Cloud) Platforms

## Table of Contents

- [Shell Helpers](#shell-helpers)
  - [Table of Contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Usage](#usage)
  - [Author Information](#author-information)
  - [License](#license)

## Requirement

Individual helpers may have individual requirements. Check the corresponding script file to determine what is needed.

## Usage

A helper comes in the form of a single-file shell script.

Each helper can be _sourced_ using the `.` syntax:

```shell
# load the helper
. helper.sh
```

Once loaded, the helper's variables and functions are available to the script that sourced the helper.

### Helpers

The repository currently includes the following helpers:

| helper        | description                      | example                     |
|---------------|----------------------------------|-----------------------------|
| `./colors.sh` | Colorization and Styling Helpers | `./examples/test_colors.sh` |

## Author Information

This repository is maintained by the contributors listed on [GitHub](https://github.com/operatehappy/shell-helpers/graphs/contributors).

## License

Licensed under the Apache License, Version 2.0 (the "License").

You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an _"AS IS"_ basis, without WARRANTIES or conditions of any kind, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
