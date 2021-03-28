[npm]: https://www.npmjs.com/package/levibostian/npm-module-blanky

Latest (recommended) [![npm latest version](https://img.shields.io/npm/v/levibostian/npm-module-blanky/latest.svg)][npm]
Beta: [![npm beta version](https://img.shields.io/npm/v/levibostian/npm-module-blanky/beta.svg)][npm]
Alpha: [![npm alpha version](https://img.shields.io/npm/v/levibostian/npm-module-blanky/alpha.svg)][npm]

[![codecov](https://codecov.io/gh/levibostian/npm-module-blanky/branch/main/graph/badge.svg?token=XXXXXXX)](https://codecov.io/gh/levibostian/npm-module-blanky)

# npm-module-blanky

Opinionated boilerplate used to make and deploy npm modules.

# Goals of this project

- Contain configuration files to setup all tools I tend to use in my development flow.
- Clone, rename some files, and get developing!
- Start with zero dependencies. I try my best to keep all npm modules as slim as possible.
- Setup with continuous delivery to npmjs.com.
- Publish source maps and Typescript type declarations.

# Getting started

- Enable GitHub Actions for your repository.
- If you have not done so already, create a GitHub account for bot purposes.
- Add your bot account in the repository `/settings/access`.
- Create secrets in GitHub settings:
  - `BOT_PUSH_TOKEN` with key being a GitHub personal access token with push permission so the bot can push to the repository (the bot will be making git tags and releases on repository).
  - `CODECOV_TOKEN` with upload token for CodeCov project to upload test coverage report to codecov.
- Edit the codecov badge at the top of this file. Find the token for the badge at `https://app.codecov.io/gh/<github-username>/<name-repo>/settings/badge`
- Project is setup for public publishing by default. If you would like to make your module private, edit `publishConfig` in `package.json`.
- Delete `CHANGELOG.md` to reset it.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key))

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/levibostian"><img src="https://avatars1.githubusercontent.com/u/2041082?v=4" width="100px;" alt=""/><br /><sub><b>Levi Bostian</b></sub></a><br /><a href="https://github.com/levibostian/npm-module-blanky/commits?author=levibostian" title="Code">💻</a> <a href="https://github.com/levibostian/npm-module-blanky/commits?author=levibostian" title="Documentation">📖</a> <a href="#maintenance-levibostian" title="Maintenance">🚧</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
