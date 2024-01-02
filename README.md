<h1 align=center>Zola Guava</h1>

<p align="center">
  <img src="https://img.shields.io/github/languages/code-size/semanticdata/zola-guava" />
  <img src="https://img.shields.io/github/repo-size/semanticdata/zola-guava" />
  <img src="https://img.shields.io/github/commit-activity/t/semanticdata/zola-guava" />
  <img src="https://img.shields.io/github/last-commit/semanticdata/zola-guava" />
  <img src="https://img.shields.io/website/https/semanticdata.github.io/zola-guava.svg" />
</p>

## Introduction

Guava is a [Zola](https://www.getzola.org) theme. It is currently a work-in-progress.

Check out the live [Demo](https://miguelpimentel.do/zola-guava/).

## Features

- Landing page (About page)
- Blog section
- Projects section (with optional project pages)
- Font Awesome Icons (used in the homepage)

## Requirements

Before using the theme, you need to install at least [Zola](https://www.getzola.org/documentation/getting-started/installation/) version 0.17.2. You can download it from the [official repo](https://github.com/)**. (_TODO Fix download link_)

## Local Development

```bash
git clone git@github.com:semanticdata/zola-guava.git
cd zola-guava
zola serve
# open http://127.0.0.1:1111/ in the browser
# you may terminate the process with `Ctrl + C`.
```

(_TODO Fix blockquote/code-block_)
<pre>git clone git@github.com:semanticdata/zola-guava.git
cd zola-guava
zola serve
You may terminate the process with <kbd>Ctrl + C</kbs>.
</pre>

**Useful Commands**

(_TODO Decide between using H3's and using _bolded_ subsections_)

| Command      | Description     |
| ------------ | --------------- |
| `zola build` | Build only      |
| `zola serve` | Build and Serve |

## Customization

In most cases you only need to modify the content in the `config.toml` file to
customize your blog.

**Custom CSS styles**

Adding your custom css is as easy as adding your own styles to the `sass/_custom.scss` file.

## Acknowledgments

Icons used in this project are part of <a href="https://uxwing.com/">UXWing</a>'s collection. Take a look at their <a href="https://uxwing.com/license">license</a>.

## License

Source code in this repository is available under the [MIT](LICENSE) license. You are free to use this code however you see fit. That said, some acknowledgement would be well received.
