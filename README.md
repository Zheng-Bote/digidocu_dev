<div id="top" align="center">
<h1>DigiDocuDev</h1>

<p>RWA for maintenance of technical documentation</p>

[Report Issue](https://github.com/Zheng-Bote/repo-template/issues) [Request Feature](https://github.com/Zheng-Bote/repo-template/pulls)

[![Apache License](https://img.shields.io/badge/License-Apache_v2.0-green.svg)](<[https://choosealicense.com/licenses/mit/](http://www.apache.org/licenses/LICENSE-2.0)>)
![GitHub Created At](https://img.shields.io/github/created-at/Zheng-Bote/digidocu_dev)

</div>

> \[!WARNING]
> README ist still under heavy construction.

<hr>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Description](#description)
    - [Features](#features)
  - [Status](#status)
    - [Repo](#repo)
    - [Readme](#readme)
    - [Markdown files](#markdown-files)
    - [Application](#application)
- [Installation](#installation)
  - [Dependencies](#dependencies)
  - [folder structure](#folder-structure)
  - [Usage/Examples](#usageexamples)
- [API Reference](#api-reference)
  - [Inputs](#inputs)
  - [Outputs](#outputs)
  - [Parameters](#parameters)
- [Documentation](#documentation)
  - [Architecture](#architecture)
    - [Product View](#product-view)
    - [Process](#process)
  - [Comments](#comments)
  - [Screenshots](#screenshots)
- [Authors and License](#authors-and-license)
  - [License](#license)
  - [Authors](#authors)
    - [Code Contributors](#code-contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<hr>

# Description

![QT](https://img.shields.io/badge/5-6-41CD52?logo=qt)
![CXX](https://img.shields.io/badge/C++-17|20-blue?logo=cplusplus)
![Rust](https://img.shields.io/badge/Rust-Rocket-lightgrey?logo=rust)

[digidocu](https://www.digidocu.dev/) is a rich web application that can be used to create redundancy-free, multilingual documentation.

Optimized for maintenance of technical documentation.

### Features

- \[x] Apache license v2.0
- \[x] works as designed
- \[ ] no bugs
- \[x] some more or less usefull Github Actions

<p align="right">(<a href="#top">back to top</a>)</p>

## Status

### Repo

![Status](https://img.shields.io/badge/Status-works-green)
![GitHub Release Date](https://img.shields.io/github/release-date/Zheng-Bote/digidocu_dev)

![GitHub Issues](https://img.shields.io/github/issues/Zheng-Bote/digidocu_dev)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Zheng-Bote/digidocu_dev)

### Readme

[![Repo - create Repo-Tree in README.md](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-create_tree_readme.yml/badge.svg)](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-create_tree_readme.yml)
[![Repo - add Actions In/Out to README](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-actions_docu.yml/badge.svg)](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-actions_docu.yml)

[![Repo - update Readme](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-call_Readme.yml/badge.svg)](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-call_Readme.yml)

### Markdown files

[![Repo - create TOC of Markdown files](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-create_doctoc_md.yml/badge.svg)](https://github.com/Zheng-Bote/digidocu_dev/actions/workflows/repo-create_doctoc_md.yml)

create ToC in Markdown files in folders

- .github/actions/\*\*
- .github/workflows/\*\*
- dist/\*\*
- docs/\*\*

### Application

> \[!CAUTION]
> [digidocu versions ≤ v2](https://www.digidocu.dev/architecture_v1-2.html) with QT5 | QT6 and Vanilla Javascript/Vue2 are outdated and deprecated.

> \[!NOTE]
> [digidocu versions ≥ v3](https://www.digidocu.dev/architecture_v3.html) are based on Rust and Angular/Vue3 and still maintained.

<p align="right">(<a href="#top">back to top</a>)</p>

# Installation

bla bla ... everything easy and green with No Code/Low code and without any costs

## Dependencies

bla bla ... with a little help from my friends

## folder structure

<!-- readme-tree start -->
```
.
├── .github
│   ├── actions
│   │   └── doctoc
│   │       ├── README.md
│   │       ├── action.yml
│   │       └── dist
│   │           ├── index.js
│   │           ├── index.js.map
│   │           ├── licenses.txt
│   │           └── sourcemap-register.js
│   └── workflows
│       ├── repo-actions_docu.yml
│       ├── repo-call_Readme.yml
│       ├── repo-create_doctoc.yml_
│       ├── repo-create_doctoc_md.yml
│       └── repo-create_tree_readme.yml
├── README.md
├── docs
│   └── img
│       ├── functional_process_current.png
│       └── product_view_current.png
├── src
│   └── .gitkeep
└── tree.bak

8 directories, 16 files
```
<!-- readme-tree end -->

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage/Examples

bla bla ... usage is intuitive and runs mostly automatically with no needs of any knowledge

```HTML
<mark> under construction </mark>
```

<p align="right">(<a href="#top">back to top</a>)</p>

# API Reference

<hr>

![GHA](https://img.shields.io/badge/Github-Action-black?logo=githubactions)

_Inputs/Outputs will be filled automatically by `.github/workflows/repo-actions_docu.yml`_

## Inputs

## Outputs

<hr>

<p align="right">(<a href="#top">back to top</a>)</p>

## Parameters

**Workflow or program**

| Parameter    | Type     | Description                          |
| :----------- | :------- | :----------------------------------- |
| `name`       | `string` | _Optional_ name-of-copyright-holder  |
| `created`    | `string` | _Optional_ <YYYY>                    |
| `version`    | `string` | _Optional_ \<v0.0.0>                 |
| `link_left`  | `string` | _Optional_ link-to-contact-page      |
| `link_right` | `string` | _Optional_ link-to-legal-notice-page |

<p align="right">(<a href="#top">back to top</a>)</p>

# Documentation

see also: [https://www.digidocu.dev/architecture_v3.html](https://www.digidocu.dev/architecture_v3.html)

## Architecture

### Product View

![product view](docs/img/product_view_current.png)

### Process

![functional process](docs/img/functional_process_current.png)

<p align="right">(<a href="#top">back to top</a>)</p>

## Comments

> \[!CAUTION]
> [digidocu versions ≤ v2](https://www.digidocu.dev/architecture_v1-2.html) with QT5 | QT6 and Vanilla Javascript/Vue2 are outdated and deprecated.

> \[!NOTE]
> [digidocu versions ≥ v3](https://www.digidocu.dev/architecture_v3.html) are based on Rust and Angular/Vue3 and still maintained.

<p align="right">(<a href="#top">back to top</a>)</p>

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

<p align="right">(<a href="#top">back to top</a>)</p>

# Authors and License

## License

[![Apache License](https://img.shields.io/badge/License-Apache_v2.0-green.svg)](<[https://choosealicense.com/licenses/mit/](http://www.apache.org/licenses/LICENSE-2.0)>)

Copyright (c) 2019 ZHENG Robert

Licensed under the **Apache License, Version 2.0** (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.

## Authors

- [![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

### Code Contributors

![Contributors](https://img.shields.io/github/contributors/Zheng-Bote/repo-template?color=dark-green)

[![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

<hr>

:vulcan_salute:

<p align="right">(<a href="#top">back to top</a>)</p>
