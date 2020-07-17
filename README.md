# hugo-example

An draft site with a draft theme.

This was created using the following commands
```
hugo new site quickstart
cd quickstart
hugo new theme draft
echo 'theme = "draft"' >> config.toml
```

## Configuring a theme

If you prefer to use an existing theme, you can check out the code, then update the config.toml file.

```
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
sed -i.bk -e 's/theme = "draft"/theme = "ananke"/g' config.toml
```

## Reference

https://gohugo.io/getting-started/quick-start/

https://discourse.gohugo.io/t/creating-a-minimal-working-template/135

https://themes.gohugo.io/
