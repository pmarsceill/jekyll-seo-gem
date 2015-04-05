# jekyll-seo-gem
A gem version of @bhardin's SEO Jekyll tool (https://github.com/bhardin/jekyll-seo-script)

## Usage
### Install the gem
`bundle install jekyll-seo`

### Run the `jekyll-seo` command

Use the `-k` flag to input specifc keywords to check against.

```
$ jekyll-seo -k "optimize jekyll for seo" _site/2012/06/open-source-attribution/index.html`
```

### Output
```
Analyzing Post: _site/2012/06/open-source-attribution/index.html...

Article Heading: true (2)
Page title: true (1)
Content: true (12)
Meta description: true (1)
```
