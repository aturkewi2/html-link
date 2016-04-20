# HTML Links

## Overview

In this lesson we will do a quick review of HTML links from the video lecture in the prior lesson.

## What's Covered in This Lesson 

1. Review HTML standard and named anchor links
2. Review relative and absolute paths

## Links

Links allow us to connect our pages and sites to each other. Arguably they give the world wide web its power, by simply allowing one document to lead to the next.

```html
<a href="http://example.com">This is a text link</a>
```

Anchor link `<a>` accepts an `href` (hypertext reference) attribute points to the location of the page or content we are linking to.

```html
<a href="http://example.com">
  <img src="myimage.jpg" alt="Alternate text">
</a>
```

Anchor links can also wrap images as well as text. In fact anything we wrap a `<a>` around becomes a clickable linked item.

```html
<a href="mailto:webmaster@example.com">This an email link</a>
```

```html
<a href="tel:555-555-5555">This an phone number link</a>
```

using special formatting in our href value `mailto:` allows us to trigger email editor or cellular devices `tel:` to dial numbers.

```html
<p id="tips">Useful Tips Section</p>
<a href="#tips">Jump to Useful Tips Section</a>
```

We can also create named anchor links that will scroll to content elsewhere in the same page. This is done by giving an `id` attribute to one element, and then setting the `href` of a link to `#id` where the ids match.

### Relative and Absolute File Paths

#### Relative

`about.html`

Relative paths describe the location of resources within the same file system.

#### Absolute

`http://example.com/about.html`

Absolute paths describe the location of resources on the entire internet at large.

It is prefered that you use the relative path when linking to content within your own website. Then use absolute paths when linking to content on other remote websites.
 
## Summary

- HTML links can be defined as `<a href="myfile.html">link text here</a>`.

## Resources

- [Mozilla Dev Network - Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Element Lookup Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Element Cheatsheet](http://overapi.com/html-dom/)