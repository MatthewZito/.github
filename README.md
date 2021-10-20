# GitHub Workflows

## Reusable Workflows

- [NPM Script Run](#npm_script_run)
- [Yarn Script Run](#yarn_script_run)
- [Pnpm Script Run](#pnpm_script_run)
- [Cypress Run](#cypress_run)

### NPM Script Run <a name="npm_script_run"></a>

[![.github/workflows/npm_script_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yaml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |
| node_version | number | 16      | false    |

Precurses the execution of any npm script with a `git checkout` and `npm install`. Caches node modules.

### Yarn Script Run <a name="yarn_script_run"></a>

[![.github/workflows/yarn_script_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/yarn_script_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/yarn_script_run.yaml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |
| node_version | number | 16      | false    |

Precurses the execution of any npm script with a `git checkout` and `yarn install`. Caches node modules.

### Pnpm Script Run <a name="pnpm_script_run"></a>

[![.github/workflows/pnpm_script_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/pnpm_script_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/pnpm_script_run.yaml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |

Precurses the execution of any npm script with a `git checkout` and `pnpm install`. Caches node modules.

### Cypress Run <a name="cypress_run"></a>

[![.github/workflows/cypress_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/cypress_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/cypress_run.yaml)

| key          | type   | default | required |
|--------------|--------|---------|----------|
| build_command  | string |   'npm run build'      | false     |
| start_command | string | 'npm run serve'    | false    |

Runs Cypress in headless mode; uses npm by default.
