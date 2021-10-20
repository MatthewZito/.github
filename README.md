# GitHub Workflows

## Reusable Workflows

- [NPM Script Run](#npm_script_run)
- [Yarn Script Run](#yarn_script_run)
- [Pnpm Script Run](#pnpm_script_run)

### NPM Script Run <a name="npm_script_run"></a>

[![.github/workflows/npm_script_run.yml](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |
| node_version | number | 16      | false    |

Precurses the execution of any npm script with a `git checkout` and `npm install`. Caches node modules.

### Yarn Script Run <a name="yarn_script_run"></a>

[![.github/workflows/yarn_script_run.yml](https://github.com/MatthewZito/.github/actions/workflows/yarn_script_run.yml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/yarn_script_run.yml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |
| node_version | number | 16      | false    |

Precurses the execution of any npm script with a `git checkout` and `yarn install`. Caches node modules.

### Pnpm Script Run <a name="pnpm_script_run"></a>

[![.github/workflows/pnpm_script_run.yml](https://github.com/MatthewZito/.github/actions/workflows/pnpm_script_run.yml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/pnpm_script_run.yml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |

Precurses the execution of any npm script with a `git checkout` and `pnpm install`. Caches node modules.
