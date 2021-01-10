<div align="center">

  <!-- Title -->
  <h1>@technote-space/material-table</h1>

  <!-- Subtitle : a fork of mbrn/material-table -->
  <h4>
    a fork of 
    <code>
      <a 
        target="_blank" 
        rel="noopener noreferrer"
        href="https://material-table.com"
      >
        mbrn/material-table
      </a>
    </code>
  </h4>

  <!-- * Badges * -->
  <p>
    <section>
      <!-- build status -->
      <a href="https://github.com/material-table-core/core/actions?query=workflow%3ABuild">
        <img 
          title="Build" 
          src="https://github.com/material-table-core/core/workflows/Build/badge.svg?branch=master"
        >
      </a>
      <!-- publish status -->
      <a href="https://github.com/material-table-core/core/actions?query=workflow%3APublish">
        <img 
          title="Publish" 
          src="https://github.com/material-table-core/core/workflows/Publish/badge.svg"
        >
      </a>
      <!-- npm package -->
      <a href="https://www.npmjs.com/package/@technote-space/material-table">
        <img 
          title="npm_package" 
          src="https://badge.fury.io/js/%40material-table%2Fcore.svg"
        >
      </a>
    </section>
    <section>
      <!-- discord -->
      <a href="https://discord.com/channels/796859493412765697/">
        <img 
           alt="Discord" 
           src="https://img.shields.io/discord/796859493412765697?label=discord"
         >
      </a>    
    </section>
  </p> 
  <!-- ^^^ end badges ^^^ -->

</div>

💾 [Installation](#installation)

🎉 [Usage](#usage)

✅ [Why does this repo exist?](#about)

🚧 [Documentation](#documentation) [[contribute to the docs](https://github.com/material-table-core/website)] (_work in progress_)

⚙️ [Example code](https://material-table-core.github.io/examples) (_work in progress_)

💬 [Have a suggestion?](https://github.com/material-table-core/core/discussions)

❌ Have an existing issue/PR at `mbrn/material-table`? We are actively deploying - please feel free to open an issue/PR

💪 [How to contribute](#contributing)

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
