# RLNp2p Website

Made and deployed with [logos site-builder](https://github.com/acid-info/logos-site-builder).

# Continuous Deloyment

- `staging` branch is deployed to [staging.rlnp2p.vac.dev](https://staging.rlnp2p.vac.dev)
- `master` branch is deployed to [rlnp2p.vac.dev](https://rlnp2p.vac.dev)

# Change Process

1. Create a new working branch from `staging`: `git checkout staging; git checkout -b my-changes`;
2. Proceed with changes, push to `origin` and open a Pull Request against `staging`;
3. Once approved, merge pull request, check changes on [staging.vac.dev](https://staging.vac.dev);
4. Once ready to promote to live website, rebase master on staging: `git checkout master; git pull master; git rebase origin/staging; git push`.
