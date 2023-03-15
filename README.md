# RLNp2p Website

Made and deployed with [logos site-builder](https://github.com/acid-info/logos-site-builder).

# Continuous Integration

Two branches are built by [our Jenkins instance](https://ci.infra.status.im/):

* `master` branch is deployed to https://rlnp2p.vac.dev by [CI](https://ci.infra.status.im/job/website/job/rlnp2p.vac.dev/)
* `develop` branch is deployed to https://dev-rlnp2p.vac.dev by [CI](https://ci.infra.status.im/job/website/job/dev-rlnp2p.vac.dev/)

# Change Process

1. Create a new working branch from `develop`: `git checkout develop; git checkout -b my-changes`;
2. Proceed with changes, push to `origin` and open a Pull Request against `develop`;
3. Once approved, merge pull request, check changes on [dev-rlnp2p.vac.dev](https://dev-rlnp2p.vac.dev);
4. Once ready to promote to live website, rebase master on develop: `git checkout master; git pull master; git rebase origin/develop; git push`.
