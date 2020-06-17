---
title: Tag Plugins
description: NexT User Docs – NexT Supported Tags
---

Tag Plugin is a way to make special style contents supported by Hexo. For example, we cannot show a image with custom size in standard Markdown. And then we can use tag plugins to solve it. [Hexo has a lot of tags](https://hexo.io/docs/tag-plugins) which can help user. And Hexo also have interfaces to themes which make themes able to create their own tags. Following tags are provided by NexT:

* [Centered Quote](#Centered-Quote)
* [Note](/docs/tag-plugins/note.html)
* [Tabs](/docs/tag-plugins/tabs.html)
* [PDF](/docs/tag-plugins/pdf.html)
* [Mermaid](/docs/tag-plugins/mermaid.html)
* [Label](/docs/tag-plugins/label.html)
* [Video](/docs/tag-plugins/video.html)
* [Button](/docs/tag-plugins/button.html)
* [Caniuse](/docs/tag-plugins/caniuse.html)
* [Group Pictures](/docs/tag-plugins/group-pictures.html)
* [Link Grid](/docs/tag-plugins/link-grid.html)

These tag plugins are only available in the theme NexT. If you switch to other Hexo themes, they may cause rendering errors.

### Centered Quote

This tag will make a quote with two lines before and after it, and text quoted will be centered. When using centered quote, if we have multi-line text, and each line has a different length, the quote won't be symmetrical, so it's recommended to use when only have single line text. For example before article all after article to make a summary.

#### Usage

```html center-quote.js
{% centerquote %}Something{% endcenterquote %}
<!-- Tag Alias -->
{% cq %}Something{% endcq %}
```

#### Example

```md
{% cq %}Elegant in code, simple in core{% endcq %}
```

{% cq %}Elegant in code, simple in core{% endcq %}
