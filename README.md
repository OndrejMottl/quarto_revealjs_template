# Presentation template

Template for a general structure and style of a presentation

## General info

This template is using [Quarto](https://quarto.org/) and [Reveal.js](https://revealjs.com) to make a presentation.

## Setup

### Getting started

Getting the presentation template is easy. There are two ways to get the template:

1. If a user has a [GitHub account](https://github.com/), the easiest way is to create your own GitHub repo using this GitHub template. More details about how to use GitHub templates are on [GitHub Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
2. Use can download the latest [Release](https://github.com/OndrejMottl/quarto_revealjs_template/releases) of the Workflow as a zip file.

### Installation of Quarto

To install Quarto, follow the instructions on the [Quarto website](https://quarto.org/docs/getting-started/installation.html).

## Edits

Edit the `presentation.qmd` file to create your presentation. The file is divided into sections, each section is a slide.

See the [Quarto documentation](https://quarto.org/docs/) for more information on how to use Quarto.

### Theme

The theme is set by the `custom_theme.scss`, please adjust it to your needs.

See the [demo presentation with all functionality](https://ondrejmottl.github.io/quarto_revealjs_template/)

The default color palette is:

![Color palette](/color_palette.png)

You can adjust the colors in the `custom_theme.scss` file.

### Local rendering

After the edits, the presentation can be rendered locally either:

1. (preferred) Using your IDE (RStudio, VSCode, etc.) and the Quarto extension.
2. the command line. The command to render the presentation is:

```bash
quarto render
```

## Publishing

Once rendered, the presentation can be published on GitHub Pages. Go to repo Settings of the repository and set the Pages source `Deploy from a branch`. The webpage will render on every commit and will be available at `https://<username>.github.io/<repo_name>/`.
