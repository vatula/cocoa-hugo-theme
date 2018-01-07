# Developer Documentation

This directory contains files that are purely used in development.

The theme should continue to work even if this directory is removed.

## Getting Started

Install build tool chain

```sh
npm i
```

After editing the .less files, run

```sh
npm run build
```

Commit both `dev/less` and `static/css`.

## Files

|File                 | Description                          |
|---                  |---                                   |
|reset.less           | CSS reset script                     |
|pygments.less        | Syntax highlighting                  |
|main.less            | Main file that @includes files below |
|site.less            | Core styles                          |
|markup.less          | Styles for rendered content |
|util.less            |                                      |
|flexbox-prefixes.less|                                      |
