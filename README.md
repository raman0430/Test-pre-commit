Useful pre-commit hooks for checking Dockerfiles for issues..

Does not require to have node or dockerfilelint installed: pre-commit will fetch & install it under the hood.

The test Dockerfile in this repo was taken from here.

Usage
- repo: https://github.com/pryorda/dockerfilelint-precommit-hooks
  rev: v0.1.0
  hooks:
  - id: dockerfilelint
    stages: [commit]
dockerfilelint
Uses https://github.com/replicatedhq/dockerfilelint to lint your Dockerfile
