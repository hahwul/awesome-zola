<div align="center">
  <h1>AWESOME ZOLA</h1>
  <p>A collection of awesome Zola resources</p>
</div>

<p align="center">
<a href="https://github.com/owasp-noir/noir/blob/main/CONTRIBUTING.md">
<img src="https://img.shields.io/badge/CONTRIBUTIONS-WELCOME-000000?style=for-the-badge&labelColor=black"></a>
<a href="https://www.getzola.org/">
<img src="https://img.shields.io/badge/Zola%20Documents-000000?style=for-the-badge&logo=&logoColor=white"></a>
<a href="https://github.com/getzola/zola">
<img src="https://img.shields.io/badge/Github-000000?style=for-the-badge&logo=github&logoColor=white"></a>
<a href="https://zola.discourse.group/">
<img src="https://img.shields.io/badge/Forum-000000?style=for-the-badge&logo=discourse&logoColor=white"></a>
</p>

The official Zola documentation is excellent, and most questions can be resolved by reading it carefully. However, this collection was created for my own reference to remember various pieces of information not found in the official guides.

## Zola

Zola is a fast and flexible static site generator written in Rust. It comes as a single executable with no dependencies, making it incredibly easy to install and use. It includes many built-in features out-of-the-box, such as Sass/SCSS compilation, syntax highlighting, table of contents generation, and multilingual support, which simplifies the development setup.

Content is written in Markdown, and the Tera template engine is used to freely customize the structure and design of the website. It is well-suited for quickly building and deploying various types of websites, including blogs, portfolios, and documentation sites.

## Themes

Zola offers a wide range of themes for different kinds of websites. You can explore more themes on the official themes page.

* Official Themes List: https://www.getzola.org/themes/

## Shortcodes

[Shortcodes](https://www.getzola.org/documentation/content/shortcodes/) are a feature used within Markdown content to insert complex HTML or handle repetitive tasks easily. You can define custom shortcodes by creating template files in the `./templates/shortcodes/` directory.

* [youtube](./shortcodes/youtube.html): `{{ youtube(id='dCKeXuV...') }}`
* [mermaid](./shortcodes/mermaid.html): `{{ mermaid() }}`
* [asciinema](./shortcodes/asciinema.html): `{{ asciinema(id='123456') }}`
* [vimeo](./shortcodes/vimeo.html): `{{ vimeo(id='123456789') }}`
* [google_map](./shortcodes/google_map.html): `{{ google_map(api_key='YOUR_API_KEY', query='Tokyo Tower') }}`
* [gist](./shortcodes/gist.html): `{{ gist(username='username', id='gistid') }}`

## Sub Commands

This is a list of unofficial subcommands.

* `zola new`: https://gitlab.com/bemyak/zola-new
