![example workflow](https://github.com/bin2bin-applications/grapesjs/actions/workflows/docker-image.yml/badge.svg)

<h1 id="app:name">GrapesJS</h1>

<img id="app:logo" src="https://raw.githubusercontent.com/bin2bin-applications/grapesjs/master/logo.png" width="180" height="180"></img>

## Developer

<p>Click <a id="app:developer" href="https://grapesjs.com/">here</a> to go to developer site</p>

## Description

<p id="app:short-description">Free and Open Source Web Builder Framework</p>

<p id="app:long-description">GrapesJS is a free and open source Web Builder Framework which helps building HTML templates, faster and easily, to be delivered in sites, newsletters or mobile apps. Mainly, GrapesJS was designed to be used inside a CMS to speed up the creation of dynamic templates.</p>

## Supported Architectures

The architectures supported by this image are:

| Architecture | Available | Tag    |
| :----------: | :-------: | ------ |
|    x86-64    |    ✅     | latest |

## Version Tags

The version tags available for this image are:

|  Tag   | Available | Description                           |
| :----: | :-------: | ------------------------------------- |
| latest |    ✅     | Stable releases with Ubuntu baseimage |

## Docker Pull

```bash
docker pull ghcr.io/bin2bin-applications/grapesjs:latest
```

## Docker Run

```bash
docker run -d --volume /tmp/app:/app -p 8080:8080 ghcr.io/bin2bin-applications/grapesjs:latest
```