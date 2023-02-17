# wet-overview

## Setup

Using bundler and jekyll.

```
bundle init
```

Configure bundle install path:

```
bundle config set --local path 'vendor/bundle'
```

Add jekyll:

```
bundle add jekyll
```

Create scaffolding for site:

```
bundle exec jekyll new --force --skip-bundle .
bundle install
```

Configure .gitignore for version control:

```
touch .gitignore
```

add to .gitignore:

```
# Ignore metadata generated by Jekyll
_site/
.sass-cache/
.jekyll-cache/
.jekyll-metadata

# Ignore folders generated by Bundler
.bundle/
vendor/
```