# About Website Template

Each system will have a [Markdown](https://daringfireball.net/projects/markdown/)/[Jekyll](https://jekyllrb.com/) website to track contributions, phases, and documentation. This repo is a template for the system-about websites. 

This template is build using [Markdown](https://daringfireball.net/projects/markdown/) and [Jekyll](https://jekyllrb.com/). The [Jekyll](https://jekyllrb.com/) website uses the [Minima](https://github.com/jekyll/minima) theme. Creating and editing these websites will not require any knowledge of [Jekyll](https://jekyllrb.com/). But if interested, the setup instrucitons are available in the [github-pages-deply-jekyll repo](https://github.com/codeadamca/github-pages-deploy-jekyll).

## Website Structure

About websites will have the following structure (excluding [Markdown](https://daringfireball.net/projects/markdown/)/[Jekyll](https://jekyllrb.com/) files): 

```
project
│   README.md
│   index.markdown (blog)
│
└── _posts
│   │   <YYYY>-<MM>-<DD>-phase-1.markdown
│   │   <YYYY>-<MM>-<DD>-phase-2.markdown
│
└── phase-1
│   │   pitch.markdown
│   │   pitch.pdf
│   │   requirements-document.markdown
│   │   requirements-document.pdf
│
└── images
```

## Guidlines

The following rules shoudl be followed with each about website:

- Home page will include a brief system descrition followed by a blog list (one for each phase)
- Each pase will have blog entry named `<YYYY>-<MM>-<DD>-phase-<#>.markdown` in the `_posts` folder
- Each phase will have a folder with the original PDF pitch, PDF requirements document, and matching markdown files
- Images for blog posts and phase documents are placed in the `root/images` folder
- Images related to a phase are named with `phase-<#>-<TITLE>.<EXT>`
- All Markdown follows [Tidy](https://tidy.codeadam.ca/) guidelines

***

## Repository Resources

* [Markdown](https://daringfireball.net/projects/markdown/)
* [Jekyll](https://jekyllrb.com/)
* [Minima](https://github.com/jekyll/minima)

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="300">
</a>
