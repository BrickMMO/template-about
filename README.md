# About Website Template

Each system will have a `system-documentation` website built with [Markdown](https://daringfireball.net/projects/markdown/)/[Jekyll](https://jekyllrb.com/). This website will be used to track contributions, phases, and documentation. This repo is a template for the `system-documentation websites`. These repos are named `system-documentation`.

This template is buildt using [Markdown](https://daringfireball.net/projects/markdown/) and [Jekyll](https://jekyllrb.com/)with a slightly customized [Minima](https://github.com/jekyll/minima) theme (check the `_layouts` and `_includes` for customization). Creating and editing these websites will not require any knowledge of [Jekyll](https://jekyllrb.com/) or [Minima](https://github.com/jekyll/minima). But if interested, the setup instrucitons are available in the [github-pages-deply-jekyll](https://github.com/codeadamca/github-pages-deploy-jekyll) repo.

## Website Structure

Documentation websites will have the following structure (excluding [Minima](https://github.com/jekyll/minima) and [Jekyll](https://jekyllrb.com/) files): 

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
│   │   system-phase-1-pitch.markdown
│   │   system-phase-1-pitch.pdf
│   │   system-phase-1-requirements.markdown
│   │   system-phase-1-requirements.pdf
│
└── images
```

## Guidlines

The following rules should be followed with each `system-documentation` website:

- Home page includes a brief system descrition followed by a blog list
- Each phase will have blog entry named `<YYYY>-<MM>-<DD>-phase-<#>.markdown` in the `_posts` folder
- Each phase will have a folder with the original PDF pitch, PDF requirements document, and matching markdown files
- Phase files are named `<SYSTEM>-phase-<#>-pitch.markdown`, `<SYSTEM>-phase-<#>-pitch.pdf`, `<SYSTEM>-phase-<#>-requirements.markdown`, and `<SYSTEM>-phase-<#>-requirements.pdf`
- Images for blog posts and phase documents are placed in the `root/images` folder
- Images related to a phase are named `phase-<#>-<TITLE>.<EXT>`
- All Markdown follows [Tidy](https://tidy.codeadam.ca/) guidelines

> This repo is available to view at  
> https://brickmmo.github.io/template-documentation-jekyll/

> **Warning**  
> This template will not be used. The `documentation-system` websites will be coded using Markdown.

***

## Repository Resources

* [Markdown](https://daringfireball.net/projects/markdown/)
* [Jekyll](https://jekyllrb.com/)
* [Minima](https://github.com/jekyll/minima)

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="300">
</a>
