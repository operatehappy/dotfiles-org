# Organization-specific Dotfiles for @operatehappy

> This repository is a collection of organization-specific `dotfiles` for [@operatehappy](https://github.com/operatehappy/).

## Table of Contents

- [Organization-specific Dotfiles for @operatehappy](#organization-specific-dotfiles-for-operatehappy)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Usage](#usage)
  - [Notes](#notes)
  - [Author Information](#author-information)
  - [License](#license)

## Background

The contents of this repository constitute the organization-specific configuration that is used during development and maintenance of [@operatehappy](https://github.com/operatehappy/) projects.

The contents of this `dotfiles-org` repository are expected to be on the same level as a project's main directory:

```sh
.
|-- dotfiles-org
|-- <other directories>
`-- sample-project
```

## Usage

Clone this repository, preserving the original directory name:

```sh
git clone git@github.com:operatehappy/dotfiles-org.git ./dotfiles-org
```

## Notes

The projects that consume this repository's contents (`dotfiles-org`) do not depend on a full Git history. That is to say: it is perfectly fine to make a shallow clone, using the `--depth=1` option.

## Author Information

This module is maintained by the contributors listed on [GitHub](https://github.com/operatehappy/dotfiles-org/graphs/contributors)

Development of this module was sponsored by [Operate Happy](https://github.com/operatehappy).

## License

Copyright 2019 [Kerim Satirli](https://github.com/ksatirli)

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at [apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an _"AS IS"_ basis, without WARRANTIES or conditions of any kind, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
