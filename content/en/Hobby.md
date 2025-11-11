---
type: 'slide'
title: 'Hobby'
params:
    headless: true
    target: 'https://github.com/foxihd/hugo-brewm'
---

This is a slide with `{{</* pin */>}}` shortcode.

## Art Making

Section with `{{</* pin */>}}` shortcode.
The item order is column-based.
If images are not square, the layout will displayed as masonry style.

{{< pin "begin" >}}
{{< pin img="/static/lino.jpg" label="Lino print">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/2.svg" label="Acrylic">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/12.svg" label="Watercolor">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/8.svg" label="Ceramics" url="longxuejiao1207@hotmail.com" quote="Interested" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/9.svg" label="Sewing and embroidery" url="#my-ecommerce" quote="Interested" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/5.svg" label="Item 5">}}
{{< pin "end" >}}

## Travel

`{{</* pin */>}}` shortcode with `quote` parameter.

{{< pin "begin" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/7.svg" label="Item 1" url="#my-ecommerce">}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/8.svg" label="Item 2" url="#my-ecommerce" quote="<s>$399</s> $299" >}}
{{< pin img="https://raw.githubusercontent.com/foxihd/hugo-et-hd/master/static/svg/flowlines/9.svg" label="Item 3" url="#my-ecommerce" quote="Get Quote" >}}
{{< pin "end" >}}

## Foodie

[[footer]]
  identifier = 'linkedin'
  pageRef    = '/'
  weight     = 4
  name       = 'linkedin'
  pre        = 'linkedin'
