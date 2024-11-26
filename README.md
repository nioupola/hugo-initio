# Initio theme for Hugo

![GitHub](https://img.shields.io/github/license/nioupola/hugo-initio.svg?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/nioupola/hugo-initio.svg?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/nioupola/hugo-initio.svg?style=flat-square)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/nioupola/hugo-initio/main.svg?style=flat-square)
![GitHub closed issues](https://img.shields.io/github/issues-closed/nioupola/hugo-initio.svg?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/nioupola/hugo-initio.svg?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/nioupola/hugo-initio.svg?style=flat-square)
![GitHub watchers](https://img.shields.io/github/watchers/nioupola/hugo-initio.svg?style=flat-square)

This [Hugo-Initio](https://sl-japan.jp/) is forked from [Hugo-Initio](https://miguelsimoni.github.io/hugo-initio-site/), ported from the [Initio](http://www.gettemplate.com/info/initio/) template by [GetTemplate.com](http://www.gettemplate.com/) for [Hugo](https://gohugo.io/).

![screenshot](https://raw.githubusercontent.com/nioupola/hugo-initio/master/images/tn.jpg)

### Original Template Info

**Licensing:** Creative Commons (for more options, go to the [original template site](http://www.gettemplate.com/info/initio/))  
**Released:** Feb 21, 2014  
**Last Updated:** Feb 21, 2014  
**Version:** 1.0  
**Bootstrap:** 3.3.4 or higher  
**Libraries:** jQuery  
**Designer:** Sergey Pozhilov  

## Installation

```
$ cd /<your-hugo-site-directory>
$ git submodule add https://github.com/nioupola/hugo-initio.git themes/hugo-initio
```

More info: [hugo setup guide](https://gohugo.io/overview/installing/)

## Configuration

[Live Demo](https://sl-japan.jp/)

[Example Site](https://github.com/nioupola/hugo-initio/tree/master/exampleSite)

[config.toml](https://github.com/nioupola/hugo-initio/tree/master/exampleSite/config.toml)

### CDN

To make it works locally, you can set the `url` to a empty string.

```toml
[params.cdn]
    url = ""
```

### Sections

You can show or hide each home page section from the `config.toml`:

```toml
showSubheader = true
showServices = true
showRecentWorks = true
showDownloads = true
showClients = true
```

### Footer

You can show or hide each footer widget from the `config.toml`:

```toml
showFooterContact = true
showfooterFollowMe = true
showFooterTextWidget = true
showFooterFormWidget = true
```

### Social Networks

You can add as many social networks as you want in the `params.social` array following this template:

```toml
[[params.social]]
  title = "facebook"
  url = "https://www.facebook.com/nickname"
  icon = "fa-facebook-square"
  footer = true
  sharethis = true
  network = "facebook"
```

See the whole configuration in the [config.toml](https://github.com/nioupola/hugo-initio/tree/master/exampleSite/config.toml) file.

### Comments

Powered by [Disqus](https://disqus.com)

```toml
[params.disqus]
    site = "your-disqus-short-name"
```

Disable the comments system by leaving the `params.disqus.site` empty.

### Matomo

```toml
[params.matomo]
    server = ""
    siteID = "51"
```

Disable Matomo by leaving `params.matomo.siteID` empty.

### Google Analytics

```toml
[params.google.analytics]
    trackerID = "GA-000000000-0"
```

Disable Google Analytics by leaving `params.google.analytics.trackerID` empty.

### Almost there...

In order to see your site in action, you can run Hugo's built-in local server.

```
$ cd exampleSite
$ hugo server -t ../..
```

Now enter [`http://localhost:1313/`](http://localhost:1313/) in the address bar of your browser.

## Deployment

- [Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [More hosting and deployment options](https://gohugo.io/hosting-and-deployment/)

## Contributing

- Found a bug?
- Got an idea for a new feature?

Let me know it using the [issue tracker](https://github.com/miguelsimoni/hugo-initio/issues).
Or make it directly: [pull request](https://github.com/miguelsimoni/hugo-initio/pulls).

## License

This port is released under the MIT License. Check the [original theme license](http://www.gettemplate.com/info/initio/) for additional licensing information.

## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [Sergey Pozhilov](http://www.gettemplate.com/) for creating this awesome theme and [Miguel Simoni](https://miguelsimoni.xyz/) to make the initial port to Hugo.
