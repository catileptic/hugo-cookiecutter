## Hugo Cookie-Cutter

This is a template for Hugo websites. 

It's stripped down. It only contains some building blocks for a Hugo theme. 

### The config 

Update the `change_me` strings in `config.toml`

```
baseURL       = "replace_me"
languageCode  = "en-us"
title         = "replace_me"
theme         = "custom_theme"

[params]
  description   = "replace_me"
```

### The theme

If you build a new Hugo theme based on this cookie-cutter, don't forget to change the `theme` name in `config.toml` and the name of the directory under `themes` (currently `custom_theme`).