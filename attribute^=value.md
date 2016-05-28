# attribute^=value

Attribute Selector

##Syntax

```
[attr^=value]

```

Represents an element with an attribute named "attr" whose first value is prefixed by "vsalue".

## Example 1

Normally Anchor links in HTML are prefixed with the `#` symbol, the attribute selelctor below will help you target all anchor links on the page, any other links that's not prefixed with the `#` symbol would not be affected.

### CSS

```

a[href^='#'] {
	color: #FF0000;
	text-decoration: none;
}

```

## Example 2

An element can have multiple `class` names, for instance:

### HTML

```
<h1 class="heading important expand"></h1>
```

Only elements with class name that begins with "heading" are selected, elements with class names such as "important heading title" are ignored:

### CSS

```
h1^=heading {
	font-size: 1.5em;
	font-weight: 900;
}
```
Apply styles to the selected HTML elements.


