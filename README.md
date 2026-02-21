# setup-cim

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/qwertycxz/setup-cim/latest)](https://github.com/qwertycxz/setup-cim)
[![GitHub contributors](https://img.shields.io/github/contributors/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub Created At](https://img.shields.io/github/created-at/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub last commit](https://img.shields.io/github/last-commit/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub Release Date](https://img.shields.io/github/release-date/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub branch check runs](https://img.shields.io/github/check-runs/qwertycxz/setup-cim/master)](https://github.com/qwertycxz/setup-cim)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/qwertycxz)](https://ko-fi.com/qwertycxz)
[![GitHub Issues](https://img.shields.io/github/issues-closed/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim/pulls)
[![GitHub License](https://img.shields.io/github/license/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub Discussions](https://img.shields.io/github/discussions/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim/discussions)
[![GitHub repo file or directory count](https://img.shields.io/github/directory-file-count/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub repo size](https://img.shields.io/github/repo-size/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub followers](https://img.shields.io/github/followers/qwertycxz)](https://github.com/qwertycxz)
[![GitHub forks](https://img.shields.io/github/forks/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)
[![GitHub User's stars](https://img.shields.io/github/stars/qwertycxz)](https://github.com/qwertycxz)
[![GitHub watchers](https://img.shields.io/github/watchers/qwertycxz/setup-cim)](https://github.com/qwertycxz/setup-cim)

This action install a version of [CIM](https://github.com/feraxhp/cim), add it to the PATH, and cache it.

Arm64 and x64 architectures are both supported.

## Usage

See [action.yml](./action.yml).

```yml
- uses: qwertycxz/setup-cim@master
  with:
    # The path of CIM.
    # Default: ${{ runner.temp }}/cim.
    path: ''
    # The repository of CIM.
    # Default: https://github.com/feraxhp/cim
    repository: ''
    # The branch, tag or SHA of CIM.
    # Default: the latest commit of the default branch.
    revision: ''
- run: cim -V
```

## Permissions

```yml
permissions:
  contents: read
```

## Requirements

For those are using GitHub-hosted runners, you are good to go.

For self-hosted runners, here are the requirements:

- [Bash](https://www.gnu.org/software/bash)
- [Git](https://git-scm.com) ⩾ 2.49.0
- [Node.js](https://nodejs.org) ⩾ 16.0
- [Rust](https://www.rust-lang.org) and [Cargo](https://doc.rust-lang.org/cargo)

## Contributions

[Issue](https://github.com/qwertycxz/setup-cim/issues) and [Pull-Requests](https://github.com/qwertycxz/setup-cim/pulls) are both welcome.

## License

[Apache 2.0](./LICENSE) © qwertycxz
