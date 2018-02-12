# jekyll-seo-gem

[![Gem Version](https://badge.fury.io/rb/jekyll-seo.svg)](https://badge.fury.io/rb/jekyll-seo)

A gem version of @bhardin's SEO Jekyll tool (https://github.com/bhardin/jekyll-seo-script)

## Usage
### Install the gem
`gem install jekyll-seo`

### Run the `jekyll-seo` command

Use the `-k` flag to input specifc keywords to check against, and the `-p` flag to specify the path to the post.

```
$ jekyll-seo -k "welcome to jekyll" -p _site/jekyll/update/2015/04/05/welcome-to-jekyll.html
```

### Output
```
Analyzing Post: _site/jekyll/update/2015/04/05/welcome-to-jekyll.html...

Article Heading: true (1)
Page title: true (1)
Content: true (1)
Meta description: false (0)
```
