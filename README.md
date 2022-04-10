# Shared Github Actions

See [`usage-stats`'s deploy workflow](https://github.com/anime-skip/usage-stats/blob/main/.github/workflows/deploy.yml) for an example of how to consume these shared workflows.

When using these workflows/actions, lock them down to a specific revision like so: `anime-skip/github-actions/.github/workflows/deploy-go-docker-image.yml@v2`

Revisions are simple incrementing numbers when inputs change, there is no semver

> When upgrading between revisions, check out the diff so you know which inputs need to be added
