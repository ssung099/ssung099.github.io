---
author: "SeungHyun Sung"
title: "Setting up a Web Server with Hugo"
date: "2026-03-28"
tags: 
- hugo
---

## Setting Up a Web Server with Hugo

## What is Hugo?
Hugo is an open-source, static site generator built in Go. It is a very useful and flexible framework for building websites that natively supports Markdown as the content format. Hugo also has many predefined themes that can be easily imported into your website for a quick setup.

### Installation
Before we can start creating a website, we need to first install hugo.
https://gohugo.io/installation/

On macOS, we can use the command `brew install hugo`.
On Windows, we can use the command `choco install hugo-extended`.

You can check that it was successfully installed by running `hugo version`.

### Set Up
1. Create a new hugo site using the command `hugo new site <username>.github.io`
2. `cd <username>.github.io` to go to the hugo site directory
3. To start the hugo server, run the command `hugo server`.

The web server should be available at `http://localhost:1313/`.

However, we will only see "Page Not Found" when visiting the url above since we have not added any content to our site.
![alt text](image.png)

### Themes
Before adding specific content, we can import one of the many provided themes that hugo provides to us.
https://themes.gohugo.io/

For example's sake, I will be choosing
### hugo.toml

### Layout Styling

## Add submodules for related githubs

## 