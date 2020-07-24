---
authors:
 - Lawrence Lane
date: 2020-07-18
title: How to Set Up Hugo for Documentation
hero: "/images/how-to-setup-hugo-for-documentation/set-up-hugo.png"
weight:
description: Learn how to setup your computer to leverage Hugo as part of a docs-as-code toolchain.
---

This article walks you through how to quickly get set up with [Hugo](http://gohugo.io/), a static site generator, to publish technical documentation in [Markdown](https://www.markdownguide.org/). This documentation toolchain works for organizations on any level, from open-source communities to enterprise-level tech giants.

Hugo is just one of many site generators that can be used. You're welcome to try others, such as [Jekyll](https://jekyllrb.com/), [Docusaurus](https://v2.docusaurus.io/), or [Gatsby](https://www.gatsbyjs.org/)---but Hugo is my personal favorite.

# Prerequisites

- Download a text/source-code editor. I recommend [Atom](https://atom.io/)
- Install the Markdown-Writer package for Atom & load its keybindings
- Create a [GitHub](https://github.com/) account

# Set Up Hugo

## 1. Install Hugo

### Mac

1. Ensure that you have the package manager [Homebrew](https://brew.sh/) on your computer.
2. Open the terminal.
3. Run the following:
   ```shell
   brew install hugo
   ```
4. Verify your installation worked with the following command:
   ```shell
   hugo version
   ```

### Windows 10

1. Ensure that you have a package manager, such as [Chocolatey](https://chocolatey.org/), on your computer.
2. Open the Command Prompt.
3. Run the following"

    ```shell
    choco install hugo-extended
    ```
4. Verify your installation worked with the following command:

   ```shell
    hugo version
    ```

## 2. Create a New Site

The following steps create a folder with your site name which includes all of the basic assets needed to get started.

1. Open a terminal window.
2. Navigate to the folder you wish to create a new project in.
3. Run the following:

```shell
hugo new site [sitename]
```

Unsure of how to navigate across folders in the terminal? Jump to the [Terminal Tips](#terminal-tips) section.

## 3. Import a Theme

The quickest way to get started is to import an existing [theme](https://themes.gohugo.io/) that you can either use outright our modify to fit your needs.

### Find a Favorite Theme

1. Scroll through the themes and pick your favorite. Select **Demo** to preview a live version.
2. Navigate to GitHub by selecting **Download** on one of the theme pages.
3. Select the **Code** button.
4. Copy the URL provided under **Clone with HTTPS**.

### Clone the Theme

1. Open a terminal window.
2. Navigate to the `themes` folder in your project: **sitename** > **themes**.
3. Run the following:
```shell
git clone <your theme url>
git submodule update --init --recursive
```

This pulls the theme's information into your project for you to use and adds it to a `.gitmodule` file which directs your site to its resources when building.

## 4. Update Configuration

There are a few details we need to square away before you can preview your fresh, new site.

### Use the Example Site for Reference

Almost every Hugo theme comes with the demo site nested in its contents. This enables you to see how they built it. This also enables you to _copy_ the basic configuration in the `config.yaml` or `config.toml` file, and paste that content into your fresh, almost-empty `config` file.

1. Open your project in your text/source-code editor.
2. Expand the **themes** folder. Select the theme you installed.
3. Expand the **exampleSite** folder.
4. Open the **config** file.
5. Copy everything.
6. Navigate to your _project's_ **config** file. This is typically the last file at the bottom. It is not nested in any other folder.
7. Paste the content and save.


# Terminal Tips

- Use the command `cd [foldername]` to go _into_ a folder
- Use the command `cd ..` to go _backwards_ one folder.
- Use the command `cd [foldername]/[foldername]/[foldername]` to jump many levels deep more quickly.
