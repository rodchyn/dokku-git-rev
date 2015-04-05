# `git rev-parse HEAD` in dokku env

Lets you fetch the git revision hash used to build the app from the `GIT_REV`
environment variable.

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/rodchyn/dokku-git-rev
dokku plugins-install
```

The environment variable will be set next time you deploy.
