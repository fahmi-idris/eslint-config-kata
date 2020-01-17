# Contributing Guidelines

## The Five Golden Rules

The simple steps of contributing to any GitHub project are as follows:

1.  [Fork the repository](https://github.com/kata-ai/eslint-config-kata/fork)
2.  Create your feature branch: `git checkout -b my-new-feature`
3.  Commit your changes: `git commit -am 'Add some feature'`
4.  Push to the branch: `git push -u origin my-new-feature`
5.  Create a [Pull Request](https://github.com/kata-ai/eslint-config-kata/pulls)!

To keep your fork of in sync with this repository, [follow this guide](https://help.github.com/articles/syncing-a-fork/).

## Prerequisites

### Windows, macOS and Linux

- [Git](http://git-scm.com/)
- [Node.js](http://nodejs.org/) (10.0.0+)
- [Yarn](https://yarnpkg.com/)
- Text Editor with [EditorConfig](http://editorconfig.org/) & [Prettier](https://prettier.io/) support. (We recommend [Visual Studio Code](https://code.visualstudio.com/))

## Development guide

Install dependencies using [Yarn](https://yarnpkg.com).

```sh-session
$ yarn
```

To build the package for publishing, run:

```sh-session
$ yarn publish
```
