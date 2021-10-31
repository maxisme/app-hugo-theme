# development

## hugo
```
hugo server
```
## sass
```
sass themes/static/css/style.sass themes/static/css/style.min.css --style compressed --watch
```

# setup

```
hugo mod init github.com/maxisme/NEW-APP
git submodule add https://github.com/maxisme/app-hugo-theme themes/app-hugo
```

Add `theme = "app-hugo"` to your `config.toml`.

Create file `content/_index.md`
```markdown
---
title: "Example"
description: "Lorem Ipsum"
keywords: "foo, bar, baz"
draft: "false"
---
```
and `static/images/icon.ico`, `static/images/logo.png`, `static/images/og_logo.png`