# Verdaccio (additional notes)

## Installation

During installation, ensure `verdaccio/conf/config.yaml` file exists.

[Generate a htpasswd entry](https://hostingcanada.org/htpasswd-generator/) and add it to `verdaccio/storage/htpasswd`

## NPM usage

Create a `.npmrc` file in the package directory with:

```
strict-ssl=false
```

In case of certificate/SSL errors during npm commands, prefix the command with `NODE_TLS_REJECT_UNAUTHORIZED=0`.

Example: `NODE_TLS_REJECT_UNAUTHORIZED=0 npm adduser --registry=https://npm.dd`
