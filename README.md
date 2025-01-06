## Setup

```sh
$ git clone https://github.com/starry99/catbook
$ jekyll serve

# Now you can start customization!
```

## Make it yours

If you want to create a new category, you need to create `*name*.html` in the `categories` folder. And add the following content:
```html
---
layout: page
type: *name*
---

{% include archive.html %}
```
Then the number of pages in the category will be displayed.
