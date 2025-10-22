# 🧩 Hugo Blog — Local Setup & Debug Guide

This guide explains how to install Hugo, run your site locally, and debug builds **exactly like GitHub Actions** — so you can catch problems before pushing.

```
sudo apt update
sudo apt install golang
```

Get latest hugo (do not install from repository, because it is very old)

Download from [here](https://github.com/gohugoio/hugo/releases/download/v0.152.0/hugo_extended_0.152.0_linux-amd64.deb)

Please check it is the latest EXTENDED version, else compilation with fail

Check the [release page](https://github.com/gohugoio/hugo/releases/tag/v0.152.0)


Run hugo
```
/usr/local/bin/hugo version
/usr/local/bin/hugo server -D
/usr/local/bin/hugo server -D --disableFastRender --disableLiveReload
```


## Bug
We yet do not know why github deployment action must be rerun in order the site to appear correctly online



