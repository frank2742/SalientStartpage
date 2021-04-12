# Salient Startpage

![./themes/demo/SalientStartpage.gif](./themes/demo/SalientStartpage.gif)

A startpage with **light/dark mode**, **automatic favicons per site**, and **retained search bar focus**.

This is compatible with [Homer](https://github.com/bastienwirtz/homer), you can copy/paste your sites/urls/icons from there to `config.yaml`.

The startpage itself can be rendered to an `.html` file with a directoy of images. Download and install both:

* [Hugo](https://gohugo.io/getting-started/installing/)
* [NodeJS](https://nodejs.org/en/download/)

# Testing

You can download and test this code by doing

```
git clone https://github.com/frank2742/Homepage
cd Homepage
npm install
npm run serve
```

# Building

To build a static html page with images (to ./public/), run

``npm run build``

`npm run build` downloads the favicons for each site defined in [`config.yaml`](./config.yaml), and tells Hugo to build for production.

I run `npm run build` after adding new bookmarks, to publish those changes.

Your startpage will be at `./public/index.html`.
