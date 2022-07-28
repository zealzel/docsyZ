---
title: 圖片
linkTitle: 圖片
weight: 4
resources:
- src: "*.jpg"
---

## Markdown
### image from static folder
![](/img2.jpg)

### from images in page folder
![](../a001.jpg)

## Shortcode
### imgproc
{{< imgproc a003 Resize "400x" >}}
{{< /imgproc >}}

### figure
{{< figure src="/img2.jpg" width=400 title="Steve Francia" >}}

### References
* https://gohugo.io/content-management/image-processing/
