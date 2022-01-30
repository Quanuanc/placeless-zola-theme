# Placeless
> This is a [Zola](https://www.getzola.org) theme, ported from [placeless-jekyll-theme](https://github.com/placeless/placeless-jekyll-theme).

![](https://gitee.com/antfly2021/PicGo-IMG/raw/master/uPic/60J5Qf.png)

## Demo

[quanuanc.github.io](https://quanuanc.github.io)

## Usage

Option A: clone the theme directly into your Zola site folder:

```
$ git clone https://github.com/Quanuanc/placeless-zola-theme.git themes/placeless
```

Option B: include it as a git submodule (it's better if you plan to use CI builders):

```
$ git submodule add https://github.com/Quanuanc/placeless-zola-theme.git themes/placeless
```

Then in your `config.toml` set:

```toml
theme = "placeless"

# Sass compilation is required
compile_sass = true