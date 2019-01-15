 [![Code Climate](https://img.shields.io/codeclimate/maintainability/alxshelepenok/gatsby-starter-lumen.svg)](https://codeclimate.com/github/osiman/gatsbyjs)  [![Twitter](https://img.shields.io/twitter/url/https/github.com/alxshelepenok/gatsby-starter-lumen.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https://github.com/osiman/gatsbyjs)


## Features
+ [Lost Grid](http://lostgrid.org/) ([peterramsing/lost](https://github.com/peterramsing/lost)).
+ Beautiful typography inspired by [matejlatin/Gutenberg](https://github.com/matejlatin/Gutenberg).
+ [Mobile-First](https://medium.com/@mrmrs_/mobile-first-css-48bc4cc3f60f) approach in development.
+ Stylesheet built using SASS and [BEM](http://getbem.com/naming/)-Style naming.
+ Syntax highlighting in code blocks.
+ Sidebar menu built using a configuration block.
+ Archive organized by tags and categories.
+ Automatic RSS generation.
+ Automatic Sitemap generation.
+ Offline support.
+ [Google Analytics](https://google.com/analytics) support.
+ [Disqus](https://disqus.com/) Comments support.

## Folder Structure

```
└── src
    ├── assets
    │   ├── fonts
    │   │   └── fontello-771c82e0
    │   │       ├── css
    │   │       └── font
    │   └── scss
    │       ├── base
    │       ├── mixins
    │       └── pages
    ├── components
    │   ├── CategoryTemplateDetails
    │   ├── Disqus
    │   ├── Links
    │   ├── Menu
    │   ├── PageTemplateDetails
    │   ├── Post
    │   ├── PostTemplateDetails
    │   ├── Sidebar
    │   └── TagTemplateDetails
    ├── layouts
    ├── pages
    │   ├── articles
    │   │   ├── 2017-05-20---Proje-Süreçlerinde-Geliştirilebilir-Arayüz
    │   │   ├── 2018-01-05---React-Redux-ile-Uygulama-Geliştirmek
    │   └── pages
    │       ├── 2018-05-01---about
    └── templates
```

## Getting Started
Install this starter (assuming Gatsby is installed) by running from your CLI:

`gatsby new repo https://github.com/osiman/gatsbyjs`

#### Running in Development
`gatsby develop`

#### Building
`gatsby build`

#### Deploy with Netlify

[Netlify](https://netlify.com) CMS can run in any frontend web environment, but the quickest way to try it out is by running it on a pre-configured starter site with Netlify. Use the button below to build and deploy your own copy of the repository:

<a href="https://app.netlify.com/sites/gatsby-oski/overview" target="_blank"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

After clicking that button, you’ll authenticate with GitHub and choose a repository name. Netlify will then automatically create a repository in your GitHub account with a copy of the files from the template. Next, it will build and deploy the new site on Netlify, bringing you to the site dashboard when the build is complete. Next, you’ll need to set up Netlify’s Identity service to authorize users to log in to the CMS.


