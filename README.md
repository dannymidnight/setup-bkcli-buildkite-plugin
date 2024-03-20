# Setup `bk` CLI

Installs the Buildkite [CLI](https://github.com/buildkite/cli) for use on [Buildkite](https://buildkite.com) Pipelines.

## Example

```yaml
steps:
- name: Deploy
  plugins:
    - dannymidnight/setup-bkcli
  command: bk version
```
