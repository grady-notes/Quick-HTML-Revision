# Structure of an HTML page and tags

A basic HTML page should have te following structure

- HTML opening
- A HEAD tag (contains all the information for the browser & does not have any visual representation on the webpage)
- A BODY tag (contains everything that is necessary for the isual representation or everything that has to be displayed on the webpage)

Basic syntax is as shown below.

```
<!DOCTYPE html>
<html>
    <head>
        <title> page title </title>
    </head>
    <body>
        content goes here
    </body>
</html>
```

# Structure of a tag

An HTML tag is a non heirarchical keyword or a term assigned to a piece of information used to surround some content & apply a special meaning to it so that the browser can understand the given instruction correctly.

An element is a basic building block of HTML & its typically made up of two seperate tags, an opening tag & a closing tag.

For Example :-
<u>UNDERLINE</u>
this is an example of the underline tag which has an opening & a closing tag.
Angle brackets help the browser to understand a tag. The "/" symbol instructs the browser to close a tag.

Not all elements have a closing tag. Some of which are,

- `<hr>` - adds a horizontal line in webpage
- `<br>` - adds a line break
- `<img>` - used to add an image in the webpage
- `<input>` - used to add an input field where the user can enter some information
- `<link>` - used to link other files, documents, other webpages & different parts of the same page.

Tag attribute is a key-value pair that keeps additional information about the opening tag it is applied to.

head tag contains 6 diffferent tags name `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` each with a closing tag. Their purpose is to define a heading in the HTML document. Compairing all the 6 tags, `<h1>` is the most important & `<h6>` is the least. It means that the `<h1>` tag displays the biggest text in terms of size & decreases as we move on towards the `<h16>` tag which is the smallest in comparision with the other 5 tags.

They can be used as page titles, individual headings, headings for paragraphs and/or sub-paragraphs, or headings to any section that the tag is supposed to introduce. They provide additional information on the tructural heirarchy of the document & should only be used to indicate section headings or subheadings but not as formatting elements like displaying big & bold text.
