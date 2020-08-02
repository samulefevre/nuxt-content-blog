---
title: My second Blog Post
description: Learning how to use @nuxt/content to create a blog
img: second-blog-post.jpg
alt: my secondtouch components/PrevNext.vue blog post
author:
  name: Peter
  bio: All about Peter and what he does and where he works
  img: https://images.unsplash.com/photo-1533636721434-0e2d61030955?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2550&q=80
---

# My second blog post

Welcome to my second blog post using content module

## This is a heading

This is some more info

## This is another heading

This is some more info.

## This is another heading

This is some more info !

<div class="bg-blue-500 text-white p-4 mb-4">
  This is HTML inside markdown that has a class of note
</div>

<info-box>
  <template #info-box>
    This is a vue component inside markdown using slots
  </template>
</info-box>

```js[nuxt.config.js]
export default {
  nuxt: 'is the best'
}
```

```html[my-first-blog-post.md]
<p>code styling is easy</p>
```
