# @technote-space/material-table

a fork of [mbrn/material-table](https://material-table.com)

[![npm version](https://badge.fury.io/js/%40technote-space%2Fmaterial-table.svg)](https://badge.fury.io/js/%40technote-space%2Fmaterial-table)
[![CI Status](https://github.com/technote-space/material-table/workflows/CI/badge.svg)](https://github.com/technote-space/material-table/actions)
[![CodeFactor](https://www.codefactor.io/repository/github/technote-space/material-table/badge)](https://www.codefactor.io/repository/github/technote-space/material-table)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/technote-space/material-table/blob/master/LICENSE)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- param::isFolding::false:: -->
<!-- param::isNotitle::true:: -->
<!-- param::isCustomMode::true:: -->

<p align="center">
<a href="#about">About</a>
<span>|</span>
<a href="#installation">Installation</a>
<span>|</span>
<a href="#usage">Usage</a>
<span>|</span>
<a href="#documentation">Documentation</a>
<span>|</span>
<a href="#contributing">Contributing</a>
</p>

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## About

- **We are not attempting to hijack what [`mbrn`](https://github.com/mbrn/material-table) has created**
- **We will always remain a true fork of `mbrn/material-table`**
  - We plan on pushing all changes upstream
- **We will always remain 100% compatible with `mbrn/material-table`**
  - We are here to resolve issues, not hijack a repo
- Life happens, and `mbrn` has become rather busy
- Only `mbrn` can update `material-table`
- We have chosen to support `mbrn` and `material-table` with the hopes of keeping the project alive

## Installation

#### yarn

`yarn add @technote-space/material-table`

#### npm

`npm install @technote-space/material-table`

## Usage

#### Updating `material-table`

Simply update your imports to receive the latest updates!

```diff
- import MaterialTable from 'material-table';
+ import MaterialTable from '@technote-space/material-table';
```

#### Compatibility

If you can import it from `material-table` you can import it from `@technote-space/material-table`. This will never change.

```javascript
import MaterialTable, {
  MTableAction /*, etc...*/,
} from '@technote-space/material-table';
```

## Documentation

- [Docs](https://material-table-core.com)
- [material-table API Documentation](https://material-table.com)

## Contributing

See [here](https://github.com/material-table-core) for more!
