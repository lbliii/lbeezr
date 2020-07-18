---
authors:
 - Lawrence Lane
date: 2020-07-18
title: How to Setup Hugo for Documentation
hero: "/images/how-to-become-a-technical-writer/how-to-part-1.png"
weight:
description: Learn how to setup your computer to leverage Hugo as part of a docs-as-code toolchain.
---

This article walks you through how to quickly get set up with [Hugo](http://gohugo.io/), a static site generator, to publish technical documentation in [Markdown](https://www.markdownguide.org/).

Hugo is just one of many site generators that can be used. You're welcome to try others, such as [Jekyll](https://jekyllrb.com/), [Docusaurus](https://v2.docusaurus.io/), or [Gatsby](https://www.gatsbyjs.org/)---but Hugo is my personal favorite.

# 1. Install Hugo

## Mac

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

## Windows 10

1. Ensure that you have a package manager, such as [Chocolatey](https://chocolatey.org/), on your computer.
2. Open the Command Prompt.
3. Run the following:
    ```shell
    choco install hugo-extended
    ```
4. Verify your installation worked with the following command:
   ```shell
    hugo version
    ```

# 2. Create a New Site

Use the following command to start a new project. This command creates a folder with all of the basic assets needed to get started. I recommend only running this command inside of a specific folder for your projects (eg, GitHub, MyWebsites, or Hugo).

> Unsure of how to navigate across folders in the terminal? Jump to the Terminal Tips section.

1. Open a terminal window.
2. Navigate to the folder you wish to create a new project in.
3. Run the following:
```shell
hugo new site [sitename]
```

# 3. Import a Theme

The quickest way to get started is to import an existing [theme](https://themes.gohugo.io/) that you can either use outright our modify to fit your needs.

## Find a Favorite Theme

1. Scroll through the themes and pick your favorite. Select **Demo** to preview a live version.
2. Navigate to GitHub by selecting **Download** on one of the theme pages.
3. Select the **Code** button.
4. Copy the URL provided under **Clone with HTTPS**.

## Clone the Theme

1. Open a terminal window.
2. Navigate to the `themes` folder in your project: **sitename** > **themes**.
3. Run the following:
```shell
git clone <your theme url>
```

This pulls the theme's information into your project for you to use. 


# Terminal Tips

- Use the command `cd [foldername]` to go _into_ a folder
- Use the command `cd ..` to go _backwards_ one folder.
- Use the command `cd [foldername]/[foldername]/[foldername]` to jump many levels deep more quickly.
