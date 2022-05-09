# @nuvibit/github-terraform-semantic-release-config

[**semantic-release**](https://github.com/semantic-release/semantic-release) shareable config to create release of Terraform Modules with [Github Actions](https://github.com/nuvibit/github-terraform-workflows).

## Plugins

This shareable configuration use the following plugins:

- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/git`](https://github.com/semantic-release/git)
- [`conventional-changelog-conventionalcommits`](https://github.com/conventional-changelog/conventional-changelog)

## Install

```bash
$ npm install --save-dev semantic-release @nuvibit/github-terraform-semantic-release-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@nuvibit/github-terraform-semantic-release-config"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.
