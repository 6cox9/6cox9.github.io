# Alexandru's Portfolio  

Welcome to the repository for my personal website!  

This project is based on the [Contrast theme](https://github.com/niklasbuschmann/contrast) and highlights my work, projects, and achievements.  

## Installation  

1. Fork this repository.  
2. Customize the `_config.yml` file.  
3. Deploy with [GitHub Pages](https://pages.github.com/).  

## Features  

- Dark mode support (macOS Mojave and above).  
- Responsive design.  
- Archive and pagination.  
- MathJax/KaTeX for equations.  
- Syntax highlighting.  
- Optional sidebar and comment integration.  

## Config Example  

Your `_config.yml` could look like this:  

```yaml
title: "Alexandru's Portfolio"
author: "Alexandru"
description: "Showcasing my work, projects, and achievements"
lang: "en"
show_excerpts: true
show_sidebar: true

navigation:
  - {file: "index.html", title: "Home"}
  - {file: "about.md", title: "About"}

external:
  - {title: GitHub, icon: github, url: "https://github.com/6cox9"}
  - {title: LinkedIn, icon: linkedin, url: "https://linkedin.com/in/alexandru-coca"}x
