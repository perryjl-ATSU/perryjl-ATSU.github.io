---
title:  "Introduction"
mathjax: true
layout: post
categories: media
---

![Semmelweiss logo](https://perryjl-ATSU.github.io/assets/Semmelweis.jpg)


## The Story of Ignaz Semmelweis

Ignaz Phillip Semmelweis was a 19th century physician who pioneered hand hygiene as an antiseptic procedure in modern medicine. During his work at Vienna General Hospital, he noticed that the first of the 2 clinics in the hospital had a mortality rate of 15.8%, whereas the mortality rate of the second clinic was a mere 7.6% in the year 1842.3 This higher mortality was attributed to a disease called purpureal sepsis or child-bed fever, the understanding of which was poor at that time.

## Why Is This Story Important?

It took the advent of the germ theory by Louis Pasteur in the 1860s and Robert Koch's postulates in 1890 to bring about an acceptance of what Ignaz Semmelweis had said all along. Decades later, handwashing is now considered common sense and forms the basis of prevention of infection in hospitals and at home. One can only wonder how many innocent lives would have been saved had this simple measure been accepted and instituted earlier.

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/h8OX0FNWANM" %}
