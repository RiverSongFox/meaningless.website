# Meaningless

```
hugo new posts/<slug>
hugo server
```

## Template overrides

The `layouts/default/summary-with-image.html` overrides Ananke's default
posts index template.

### Alt texts for featured images

Custom front matter param `featured_image_alt` for better A11y.

### Short post form by default

The _Read More_ button is hidden by default. The `long: true` param tells
Hugo to render the button.

## Shoutouts

This project would not be possible without open source software
and great folks sharing their knowledge on the Web;

- [Hugo, The world’s fastest framework for building websites](https://gohugo.io/)
- [Hugo: How to add support for responsive images trough image processing and page bundles <3 by Nils Norman Haukås](https://nilsnh.no/2018/06/10/hugo-how-to-add-support-for-responsive-images-trough-image-processing-and-page-bundles-3/)
