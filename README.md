# Bulma responsive form addons

> Responsive form addons for [Bulma](https://bulma.io/). 🤷

## Overview

Bulma feature cool [form addons](https://bulma.io/documentation/form/general/#form-addons)
but they're not responsive, meaning that if you abuse them, it'll look
like garbage on mobile like described in [this issue](gghttps://github.com/jgthms/bulma/issues/1694).

If you also have this problem, hello, you found the right place, because
I fixed it for you! 😌

![Preview](preview.png)

This [small piece of CSS](bulma-responsive-form-addons.css) will fix it
for you out of the box with Bulma default values of a mobile maximum
width of 768 pixels an input border radius of 4 pixels.

If you used different values, sorry, this is not SCSS, you'll have to
edit it manually. Feel free to make a PR with Sass support. ❤

Enjoy! 🍻

## Usage

```html
<link rel="stylesheet" href="bulma-responsive-form-addons.css">
```

Feel free to adapt to your build process of choice. 🙃
