# Repository template

![GitHub package.json version] ![GitHub license]

[GitHub package.json version]: https://img.shields.io/github/package-json/v/CJKay/template
[GitHub license]: https://img.shields.io/github/license/CJKay/template

This template demonstrates a simple, language-agnostic repository layout. It
includes a [`package.json`](package.json) file describing the basic metadata of
the repository, a license file, a bare-bones changelog, and configurations  for
[commitlint] and [Commitizen]. [standard-version] is included with the tools
installed by `npm install`, and it has been used to generate the changelog
boilerplate.

## License

This repository is licensed under the [BSD Zero Clause license]. As such, you
are free to re-license repositories derived from this template as you wish.

## Usage

This template includes several Node.js tools, pulled in via development
dependencies. To install these tools, use:

```sh
npm install
```

This will install the following tools within the `node_modules` directory:

- [commitlint]
- [Commitizen]
- [Husky]
- [standard-version]

It will also install a [prepare-commit-msg hook] invoking [Commitizen] and a
[commit-msg hook] invoking [commitlint], such that these tools are automatically
integrated into your normal Git workflow. These hooks are not installed globally
and will not apply outside of your newly-created repository.

[commitlint]: https://commitlint.js.org/#/
[Commitizen]: http://commitizen.github.io/cz-cli/
[Husky]: https://typicode.github.io/husky/#/
[standard-version]: https://github.com/conventional-changelog/standard-version

[prepare-commit-msg hook]: https://git-scm.com/docs/githooks#_prepare_commit_msg
[commit-msg hook]: https://git-scm.com/docs/githooks#_commit_msg

[BSD Zero Clause license]: https://choosealicense.com/licenses/0bsd/
