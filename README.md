# Website

## Developers

This repository makes use of git submodules for handling the `website-theme`. If you wish to make
modifications to the theme, it is recommended that you make these directly into the `website-theme`
repo found [here](https://github.com/rndlabs/website-theme).

### Local development

1. Clone the repository to your machine, using `--recursive` to ensure submodules are pulled.

```bash
git clone --recursive git@github.com:rndlabs/website.git
```

2. Follow the directions to [install zola](https://www.getzola.org/documentation/getting-started/installation/).

3. Before editing, create a branch so we don't pollute `main`

```bash
cd website
git checkout -b feat/new-page
zola serve
```

Now you can edit the markdown in your favourite text editor with live updates!