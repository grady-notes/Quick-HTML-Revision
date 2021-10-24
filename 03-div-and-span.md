# Div and Span (Inline and Block)

All the elements in the HTML are classified into 2 main types.

- Block level elements
- Inline elements.

The 2 most commonly & repeatedly used elements in an HTML document are the `<div>` & the `<span>`, each followed with a closing tag. They are considered as the generic container elements that do not semantically mean anything, also they do not have any visual representation in the web page. However both elementts are rendered with different properties. They should only be used when no other element is suitable.

# Block level elements

Anything before the block level elements is pushed above the content & anything after the block level elements is pushed below the content.

The `<div>` tag is an example of a block level element.

A `<div>` tag is used as follows

```
<body>
    before div tag
    <div>
        inside div tag
    </div>
    after div tag
</body>
```

# Inline elements

Inline elements do not disrupt the flow of the HTMl document also does not alter the way the text/content is displayed in the browser unlike block level elements.

The `<span>` tag is an example of a block level element.

A `<span>` tag is used as follows

```
<body>
    before span tag
    <span>
        inside span tag
    </span>
    after span tag
</body>
```

- <b>DIV & SPAN TAGS DO NOT HAVE ANY SIGNIFICANT FEATURE OR A PURPOSE IN HTML OTHER THAN GROUPING THEIR CONTENT FOR FURTHER FORMATTING.</b>

- <b>ONE KEY DIFFERENCE BETWEEN BLOCK & INLINE ELEMENTS IS THAT THE BLOCK LEVEL ELEMENTS CAN CONTAIN ANY TYPE OF ELEMENTS WHETHER BLOCK OR INLINE. BUT THE INLINE ELEMENTS CAN CONTAIN OTHER INLINE ELEMENTS ONLY.<b>
