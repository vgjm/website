# My personal website

This is the code of [vgjm.github.io](https://vgjm.github.io/).

## Create new post

```
hugo new posts/new-post.md
```

The post will be generated into `./content/posts`. Edit it and delete the `draft` field if done.

## Build

The github action defined in `./.github/workflows/deployment.yml` will build the website automatically and [github.com/vgjm/vgjm.github.io](https://github.com/vgjm/vgjm.github.io) repository will pick this everyday at 00:00 UTC.
