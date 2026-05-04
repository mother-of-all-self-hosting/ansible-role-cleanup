<!--
SPDX-FileCopyrightText: 2022 etke.cc

SPDX-License-Identifier: GPL-3.0-or-later
-->

# system/cleanup

System cleanup role

Refer to `defaults/main.yml` to get the list of options

## Development

You can optionally install a Git pre-commit hook (via [mise](https://mise.jdx.dev/) + [prek](https://prek.j178.dev/)) that runs formatting and linting checks before each commit. See [`.pre-commit-config.yaml`](./.pre-commit-config.yaml) for which hooks are to be executed.

To install the hook, run the [`just`](https://github.com/casey/just) command below:

```sh
just prek-install-git-pre-commit-hook
```
