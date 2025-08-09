# This Site

## The Language

### [Markdown](https://daringfireball.net/projects/markdown/)

I love Markdown. The one thing I don't like about Markdown is there is about 15 different specs.

![relevant xkcd](https://imgs.xkcd.com/comics/standards.png)
/// caption
///

This site strives to use [GitHub Flavored Markdown](https://github.github.com/gfm/). Anytime we have to stray from this standard, it will be documented here.

## The Editor

### [Neovim](https://neovim.io)

I use Neovim to write posts and pages. There are a few plugins that I use to make writing posts and pages easier:

* [render-markdown.nvim](https://github.com/MeanderingProgrammer/render-markdown.nvim)

I even have a custom vimwiki/neowiki plugin that I use to facilitate writing posts. I will eventually be writing a more in-depth post on how I have my Neovim setup for this. Stay tuned!

## The Site Generator

### [MkDocs](https://www.mkdocs.org/)

#### MkDocs Theme

* [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

#### MKDocs Plugins

* [mkdocs-callouts](https://github.com/sondregronas/mkdocs-callouts)

    >[!NOTE]-
    > I guess I have always used "Obsidian-style" callouts/admonitions. Github Flavored Markdown refers to these as [Alerts](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts). Standard Markdown does not have a special syntax for callouts and MkDocs does it differently than Github/Obsidian style Markdown. This plugin allows us to use these style callouts.

* [mkdocs-git-authors-plugin](https://github.com/timvink/mkdocs-git-authors-plugin)
