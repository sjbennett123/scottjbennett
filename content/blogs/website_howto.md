---
title: "Website Howto"
date: 2022-11-10T10:33:21-05:00
---

- Facebook is terrible for discoverability and fuck mark zuckerbrerg. 
  - Facebook makes it hard to find what you need.
  - Facebook makes it hard to know who is interested vs who just wants to browse
- A real website feels professional.

## Accounts to Create

### Netlify

- https://app.netlify.com/signup

### Github
- https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account

## Software to Install
### Install Github Desktop

- https://desktop.github.com

### Install Typora

- https://typora.io
- $15 to Purchase. I recommend it.
- https://support.typora.io/Install-and-Use-Pandoc
  - https://github.com/jgm/pandoc/releases/tag/2.19.2


### Install Notepad ++

- https://notepad-plus-plus.org/downloads

### Install Git

- https://git-scm.com/downloads

### Install Go

- https://go.dev/doc/install

### Install Python

- https://www.python.org/downloads/
- https://www.python.org/ftp/python/3.11.1/python-3.11.1-amd64.exe
- Install Yamllint
  - https://sourcelevel.io/blog/what-is-a-linter-and-why-your-team-should-use-it
  - pip install yamllint

### Install NodeJS

- https://nodejs.org/en/download

### Install Hugo

- https://gohugo.io/installation
- https://github.com/gohugoio/hugo/releases/download/v0.109.0/hugo_extended_0.109.0_windows-amd64.zip

### Install additional NPM Packages for Docsy  Theme

- npm install autoprefixer
- npm install postcss-cli
- npm install postcss

### Install Netlify CLI

- https://docs.netlify.com/cli/get-started
- npm install netlify-cli -g

## Discussion

### Open Source

- Freely distributed software with a permissive license 

### Markdown

- https://commonmark.org/help
- Why use markdown
  - Easy to read.
  - Good editors.
  - Converts to other formats.
    - Converting from Word using Typora.
    - Exporting to PDF with Typora.


### Yaml

- Configuration Language
- https://yaml.org
- yamllint to check that it's all good
  - https://sourcelevel.io/blog/what-is-a-linter-and-why-your-team-should-use-it
  - https://pypi.org/project/yamllint/
- Sometimes I have seen hugo use Toml. It's fine but I would prefer it all be in yaml
  - https://www.convertsimple.com/convert-toml-to-yaml/


### Hugo

- https://gohugo.io
- https://www.youtube.com/watch?v=ZFL09qhKi5I
- Static Site Generator
    - Converts Markdown to HTML.
    - Fast as hell.
    - No need to be a programmer to get off the ground.

### Hugo Frontmatter

- You are not just writing Markdown. There is a Metadata piece that goes with your documents. 
- https://gohugo.io/content-management/front-matter/

### Docsy Hugo Theme

- Not a small part it's half of the puzzle.
- Not easily switched out despite what the docs lead you to believe....
- https://www.docsy.dev/
- Docsy Example Site
  - https://github.com/google/docsy-example
  - https://example.docsy.dev/


### Running Hugo Locally

- Why do this?
  - Test Changes before sending to the website
  - Run at the campsite

- How do you do this 
  - Run from the root of the website folder
  - `hugo server -D`
  - http://localhost:1313/

### Git

- Commits/Changes
- Local and Remote
- Github Desktop Application
  - https://desktop.github.com/

- Github Web User Interface
  - https://www.github.com

- Command Line Interface
  - `git add .;git commit -m 'updates'; git push`

- Branches - Make a version of the site for Staff/NPC's or for testing. 
- Blame/Annotate - See who made a change and when.
- Binary Files - Use large file storage. This is only for Text not for Binary Files.
- Triggered "build"
  - Netlify doesn't deploy if build fails!


### Netlify

- https://docs.netlify.com/integrations/frameworks/hugo/
- Hosting Platform with very generous free tier.
- Domain Setup
- Special features!
  - Password protection for site at PRO plan
  - redirects



# Lets make this website!

## Before we get started

- This is as easy as this process can be but this is NOT a novice process it's technical and intiminating. If you decide this it too much for your needs thank you for your time I can either configure this for you or we can find a tool that works better for you like Squarespace or Wix. 
- We will be using the command line and you will need to take notes. 
- We will go as slow as the slowest person on the call.
- If you have any questions ask and we will talk it through. No need to stay confused. 
  - If you want to go over this again please let me know we can just go through any parts you have had problems with. 


## Configure Local Hugo Instance

- Hugo has steps at https://gohugo.io/getting-started/quick-start/ we are not following these steps. We are going to take a slightly different approach

- Clone Docsy Example site with github desktop. 
  - https://github.com/google/docsy-example
- confirm it runs locally
  - `hugo server -D`
  - http://localhost:1313/

- create new repository in github as a target 

- Point local docsy example to remote crestfallen repo

## Configure Netlify Integration

- add github repository in netlify ui.
- pick a subdomain.
- redirects
  - I use one for Discord and the google feedback form.
  - `public/_redirects`
- configure Netlify CLI
- confirm that build and deploy worked good

## Configure Site URL in Hugo Setup File
- update configuration file 
- push 
- confirm that we are good. Watch it build

## Configure Search in Hugo Setup File

- 

- 

## Configure Github in Hugo Setup File


## Configure Favicon

https://www.docsy.dev/docs/adding-content/iconsimages/



## Configure Large Media Setup

- https://docs.netlify.com/large-media/setup/

## Static resources

- Static Resources Folder
  - PDF
    - Layout with Affinity Designer
  - Epub
    - Convert with Typora / Panadoc
  - Maps / Large images

# Next Steps

- Escaping from facebook means that you need to start to build all of the things that facebook "does" but do it without their tools 

- Mailing list? 

  - https://buttondown.email

- 

## Printed books

- How do they relate back to your website. Which is the "cannon" source

  - Lulu

  - Mixiam

- 
