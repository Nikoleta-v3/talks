# Talks

A repository that creates a static site using [Jekyll](http://jekyllrb.com/).

The site has been deployed (https://nikoleta-v3.github.io/talks/) and is
a part of my personal site (https://nikoleta-v3.github.io/) that lists
all the talks delivered by me and my slides.

The repo has contains the files needed to generate the site:

```
.
├── _includes/
|   ├── footer.html
|   ├── head.html
|   └── header.html
├── _layouts/
|   ├── default.html
|   └── page.html
|   └── post.html
├── _sass/
|   ├── _base.scss
|   └── _layout.scss
|   └── _syntax-highlighting.scss
├── css/
├── _config.yml
├── _feed.xml
└── index.md
```

Also the `tex` files and `pdf` to generate slides for my talks
and lighting talks:

```
.
├── talks/ # tex files and pdf for talks
├── lightning-talks/ # tex files and pdf for lighting talks
```