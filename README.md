# Site Documentation 

## [dmracek.github.io](https://dmracek.github.io)

This repo is used to deploy the site and was built using [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Directory Structure

Site development and deployment are in separate GitHub repos. The development repo/folder is `my-project` found [here](https://github.com/dmracek/my-project) and the site is deployed to the current repo/folder `dmracek.github.io` using [GitHub Pages](https://pages.github.com/) found [here](https://github.com/dmracek/dmracek.github.io)

```bash
.
├── dmracek.github.io
└── my-project
    ├── docs
    ├── mkdocs.yml
    ├── README.md
    └── site

4 directories, 2 files
```

## Workflow

When ready to deploy the site, step into the current `dmracek.github.io` repo/folder and run the following in the CLI.

```
mkdocs gh-deploy --config-file ../my-project/mkdocs.yml --remote-branch master
```





