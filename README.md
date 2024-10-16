[![MAID WITH](https://img.shields.io/badge/MAID%20WITH-RUBY-red)](https://rubyinstaller.org/) [![Gem Version](https://badge.fury.io/rb/jekyll.svg)](https://badge.fury.io/rb/jekyll) [![BUILT WITH](https://img.shields.io/badge/BUILT%20WITH-SWAG-blue)](https://img.shields.io) [![PRs Welcome](https://img.shields.io/badge/PRs-WELCOME-9cf.svg?style=shields)](http://makeapullrequest.com)

<div align="center">
    <a herf="https://gdsc-deu.github.io">
        <img src="./assets/img/GDSC Logo chapter.png" width="200px" alt="GDSC DEU logo">
    </a>
    <h2 align="center"><strong>GDSC DEU Homepage</strong></h2>
    Introduce your project and write your articles at GDSC DEU!
    <p align="center">
        <a href="https://gdsc-deu.github.io"><strong>Explore GDSC DEU Homepage »</strong></a>
        <br/>
        <br/>
        <a herf="https://gdsc.community.dev/dong-eui-university/">GDSC Chapter</a>
        ·
        <a herf="https://github.com/GDSC-DEU/gdsc-deu.github.io/issues">Report Bug</a>
        ·
        <a herf="https://github.com/GDSC-DEU/gdsc-deu.github.io/issues">Request Feature</a>       
    </p>
    <hr/>
</div>

## Table of Content

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Development](#development)
- [Style Guide](#style-guide)
- [Contributing](#contributing)
- [Maintainers](#maintainers)

## Introduction

<div align="center">
    <img src="./assets/img/GDSC DEU main page.png" alt="GDSC DEU logo">
</div>
GDSC DEU members can write blog post and introduce their project at this repository. And you can read GDSC DEU information at <a href="https://gdsc-deu.github.io">https://gdsc-deu.github.io</a>.

## Prerequisites

- Ruby version **2.5.0** or higher
- RubyGems
- GCC and Make

See [prerequrisites](https://jekyllrb.com/docs/installation/#requirements) for guides and details.

## Installation

### Install Locally

Below is an example of how you can instruct your audience on installing and setting up your app.

1. Install all [prerequisites](#prerequisites).
2. Install the jekyll and bundler gems.
   ```terminal
   gem install jekyll bundler
   ```
3. Clone the repo and change into the repo's directory.
   ```terminal
   git clone https://github.com/GDSC-DEU/gdsc-deu.github.io.git
   cd ./gdsc-deu.github.io
   ```
4. Install all dependency.
   ```
   bundle install
   ```

### Using Dokcer

You can also use Docker to run the site locally.

```bash
docker run --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve
```

## Development

### Run development instance (with hot-reload)

```
bundle exec jekyll serve
```

- You can check the demo site by accessing [https://localhost:4000](https://localhost:4000).

### Directory Structure

```bash
GDSC-DEU.GITHUB.IO/
├── _data                      # Well-formatted site data.
├── _includes                  # The partials of layouts and posts.
├── _layouts                   # The templates that wrap posts.
├── _members                   # GDSC Member Information.
├── _pages                     # Website pages (that are not posts)
├── _posts                     # Where all blog posts will go.
├── _sass                      # Partials of `style.scss` file.
├── _assets                    # Style sheets and images are found here.
|  ├── css                     # CSS file go here.
|  |  └── styles.scss          # Main SCSS file.
|  └── font                    # Font file go here.
|  └── img                     # Image file go here.
├── _config.yml                # Site settings.
├── .gitignore                 # Manage untracked files.
├── 404.html                   # Custom and responsive 404 page.
├── Gemfile                    # Ruby Gemfile for managing Jekyll plugins.
├── index.html                 # Main page.
└── README.md                  # Includes all of the documentation for this site.
```

## Style Guide

- Use the **[Google HTML/CSS Guideline](https://google.github.io/styleguide/htmlcssguide.html)**.

## Contributing

1. Create issues about the work.
2. Create a branch on the issue.
3. Commit, push to the created branch.
4. When the work is completed, request a pull request to main branch after rebaseing the main branch.
5. Review the code and merge it.

### Branching

Use author name and issue number into the branch names according to the format below:

```
<author>_<issue-number>_<branch-type>_<branch-name>
```

E.g., **jiyoon_43_feature_new-experimental-changes**

### Commit Message

Referred to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

```
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```

## Maintainers

Current Maintainers:

- Jiyoon Bak (jiy00nn) - https://github.com/jiy00nn
