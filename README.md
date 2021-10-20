# GitHub Workflows

[![.github/workflows/cypress_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/cypress_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/cypress_run.yaml)
[![.github/workflows/npm_script_run.yaml](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yaml/badge.svg)](https://github.com/MatthewZito/.github/actions/workflows/npm_script_run.yaml)

## Reusable Workflows

- [NPM Script Run](#npm_script_run)
- [Cypress Run](#cypress_run)

### NPM Script Run <a name="npm_script_run"></a>

| key          | type   | default | required |
|--------------|--------|---------|----------|
| script_name  | string |         | true     |
| node_version | number | 16      | false    |

Precurses the execution of any NPM script with a `git checkout` and `npm install`.

### Cypress Run <a name="cypress_run"></a>

| key          | type   | default | required |
|--------------|--------|---------|----------|
| build_command  | string |   'build'      | false     |
| start_command | string | 'serve'    | false    |

Runs Cypress in headless mode.
