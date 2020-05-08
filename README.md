# @diegoh/tsconfig

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Package Version](https://img.shields.io/npm/v/@diegoh/tsconfig)

Base typescript config for Node.js projects.

## Usage

1. Install this module

`npm i -D @diegoh/tsconfig`

2. Integrate into your project's typescript configuration file

In your `tsconfig.json`

```json
{
  "extends": "@diegoh/tsconfig",
  "include": ["src/**/*"],
  "exclude": ["node_modules", "**/*.spec.ts"]
}
```

## Development

1. Create a new branch from `master` with a name relevant to the changes you're making. `git branch -b my-new-feature-description`
2. Push the branch and open a Pull Request (PR).
3. Request a code review.

When integrating back to the mainline commits should be **Squash merged**.

## Reference

Typescript Documentation (tsconfig.json)
<https://www.typescriptlang.org/docs/handbook/tsconfig-json.html>
