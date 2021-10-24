# List Tags

The list tags are used to display lists on the webpage.

There are 3 types of lists in HTML.

## Ordered List

These types of lists are rendered in an order using numbers or whatever attribute is specified. Each item in the list should be wrapped around the `<li> ... </li>`
The most commonly used attribute of the ordered list is the "type" attribute. It is used in a webpage as shown below.

- Numeric Ordered List (Default)

```
<body>
    <ol type="1">
        <li>One</li>
        <li>Two</li>
    </ol>
</body>
```

- Roman Numeric Ordered List

```
<body>
    <ol type="I">
        <li>One</li>
        <li>Two</li>
    </ol>
</body>
```

- Alphabetical Ordered List

```
<body>
    <ol type="A">
        <li>One</li>
        <li>Two</li>
    </ol>
</body>
```

## Unordered List

These types of lists are rendered in a random order using bullet points. Each item in the list should be wrapped around the `<li> ... </li>`
This type of list does not have any attribute, at least not in the basic course.

- Un-Ordered List (Default)

```
<body>
    <ul>
        <li>One</li>
        <li>Two</li>
    </ul>
</body>
```

## Definition List

These types of lists are rendered as the title & a paragraph. The paragraph has a default indentation which can be changed with additional formatting. Each item in the description list contains a description title wrapped in `<dt> ... </dt>` & an appropriate description data wrapped in the `<dl> ... </dl>` tags

This type of list does not have any attribute, at least not in the basic course.

- Descritption List (Default)

```
<body>
    <dl>
        <dt>Title 1</dt>
        <dd>Description 1</dd>

        <dt>Title 2</dt>
        <dd>Description 2</dd>
    </dl>
</body>
```
