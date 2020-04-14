# Copyright

The font files in this bundle are made available by Google under Apache license version 2.0.
This package is just a re-distribution of them, together with some specific non-google CSS
to use them more easily.

Check https://material.io/ respective https://fonts.google.com/specimen/Roboto for
more details about guidelines, tutorials, rights etc.

The other stuff not coming from Google, is licensed under LGPLv3 or later, but that's
just a bit of CSS.

# Usage

```css
body {
	font-family: 'Roboto', sans-serif;
	font-weight: 300;
}
```

Icons (copy&paste it to get the other stars as well):

```css
.fivestars {
	font-family: 'Material Icons';
}

.fivestars.fiveStars2::before {
	content: '\e838\e838';
}

.fivestars.fiveStars2::after {
	content: '\e839\e839\e839';
}
```

Icons as list enums:

```css
ul#your-id {
	list-style-type: none;
}

ul#your-id > li::before {
	content: '\e838';
	font-family: 'Material Icons';
	color: red;
}
```
