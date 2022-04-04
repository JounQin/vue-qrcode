<p align="center">
  <a href="https://rxjs.dev">
    <img src="https://rxjs.dev/assets/images/logos/Rx_Logo_S.png" height="50">
  </a>
  <a href="#readme">
    <img src="https://rx-ts.github.io/assets/heart.svg" height="50">
  </a>
  <a href="https://vuejs.org">
    <img src="https://vuejs.org/images/logo.png"  height="50">
  </a>
</p>

[![GitHub Actions](https://github.com/rx-ts/eslint/workflows/CI/badge.svg)](https://github.com/rx-ts/eslint/actions/workflows/ci.yml)
[![Codacy Grade](https://img.shields.io/codacy/grade/16b92cd21d844d74b399de3207ae6cb9)](https://www.codacy.com/gh/rx-ts/vue)
[![type-coverage](https://img.shields.io/badge/dynamic/json.svg?label=type-coverage&prefix=%E2%89%A5&suffix=%&query=$.typeCoverage.atLeast&uri=https%3A%2F%2Fraw.githubusercontent.com%2Frx-ts%2Fvue%2Fmaster%2Fpackage.json)](https://github.com/plantain-00/type-coverage)
[![GitHub release](https://img.shields.io/github/release/rx-ts/vue)](https://github.com/rx-ts/vue/releases)
[![David Dev](https://img.shields.io/david/dev/rx-ts/vue.svg)](https://david-dm.org/rx-ts/vue?type=dev)

[![Conventional Commits](https://img.shields.io/badge/conventional%20commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![Code Style: Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![changesets](https://img.shields.io/badge/maintained%20with-changesets-176de3.svg)](https://github.com/atlassian/changesets)

> Make [Vue][] greater with [RxTS][].

## TOC <!-- omit in toc -->

- [Homepage](#homepage)
- [Packages](#packages)
- [Install](#install)
- [Changelog](#changelog)
- [License](#license)

## Homepage

<a href="https://vue-rx.now.sh" target="_blank">vue-rx</a>

## Packages

This repository is a monorepo managed by [Changesets][] what means we actually publish several packages to npm from same codebase, including:

| Package                               | Description                                               | Version                                                                                         | Peer Dependencies                                                                                                                                            | Dependencies                                                                                                                             |
| ------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [`vue-qrcode`](/packages/vue-qrcode/) | 🤳 A Vue component for QR code generation with [qrcode][] | [![npm](https://img.shields.io/npm/v/vue-qrcode.svg)](https://www.npmjs.com/package/vue-qrcode) | [![David Peer](https://img.shields.io/david/peer/rx-ts/vue.svg?path=packages/vue-qrcode)](https://david-dm.org/rx-ts/vue?path=packages/vue-qrcode&type=peer) | [![David](https://img.shields.io/david/rx-ts/vue.svg?path=packages/vue-qrcode)](https://david-dm.org/rx-ts/vue?path=packages/vue-qrcode) |
| [`vue-qrious`](/packages/vue-qrious/) | 🤳 A Vue component for QR code generation with [qrious][] | [![npm](https://img.shields.io/npm/v/vue-qrious.svg)](https://www.npmjs.com/package/vue-qrious) | [![David Peer](https://img.shields.io/david/peer/rx-ts/vue.svg?path=packages/vue-qrious)](https://david-dm.org/rx-ts/vue?path=packages/vue-qrious&type=peer) | [![David](https://img.shields.io/david/rx-ts/vue.svg?path=packages/vue-qrious)](https://david-dm.org/rx-ts/vue?path=packages/vue-qrious) |

## Install

```sh
# yarn
yarn add vue-{qrcode,qrious,translator}

# npm
npm i vue-{qrcode,qrious,translator}
```

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](./CHANGELOG.md).

## License

[MIT][] © [JounQin][]@[1stG.me][]

[1stg.me]: https://www.1stg.me
[changesets]: https://GitHub.com/atlassian/changesets
[rxts]: https://rxjs.dev
[vue]: https://vuejs.org
[jounqin]: https://GitHub.com/JounQin
[mit]: http://opensource.org/licenses/MIT
[qrcode]: https://github.com/soldair/node-qrcode
[qrious]: https://github.com/neocotic/qrious
