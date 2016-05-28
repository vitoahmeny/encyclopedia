# Span

`span` is used for defining and applying styles to inline elements.

In HTML, the `span` tag and the `div` tag are used to grouping parts of a document so that they're identifiable when no other HTML element can accurately represent the content. The difference between `span` and `div` is that `span` is used with inline elements whilst `div` is used with block-level elements.

## Attributes

`Span` only supports HTML global attributes.

## Example 1

Change the font-weight property of the text grouped with `span`:

```
<h1>Team <span>Finder</span></h1>
```

### CSS

```
h1 span {

	font-weight: 900;
} 

```

## Example 2

Using `span` and `class` attribute to apply style to inline content:

```
<p>This is a paragraph with <span class="redtext">red text.</span></p>

```

### CSS

```
.redtext {
	color: red;
}
```

## Example 3 

Using `span` to creat text tool tips, `span` allows a title attribute appearring when the mouse is left to site on the text.

### HTML

```
<p>This is a illustration of using "span" to add text tool tips, <span title="Text tool tips, write whatever you want.">now put your mouse on me.</span></p>

```

