In HTML, an **element** is a building block of a webpage that gives content structure and meaning. Elements are usually marked up using **tags**, which are keywords enclosed in angle brackets, such as `<p>`{.html}. Most elements use an **opening tag** to mark where the element begins and a **closing tag** — written with a forward slash, such as `</p>`{.html} — to mark where it ends.

HTML elements can serve various purposes, such as:

* **Defining headings:** Heading elements such as `<h1>`{.html} to `<h6>`{.html} are used for headings of different levels.
* **Creating paragraphs:** The paragraph element, marked up with the `<p>`{.html} tag, is used for blocks of text.
* **Adding links:** The link element, marked up with the `<a>`{.html} tag, creates hyperlinks to other webpages or resources.
* **Inserting images:** The image element, marked up with the `<img>`{.html} tag, embeds an image in a webpage.

# Void Elements

Not all tags come in pairs. Some tags represent **void elements** — elements that have no content and therefore no closing tag. Common examples include `<img>`{.html} (image), `<br>`{.html} (line break), and `<hr>`{.html} (horizontal rule). These tags form an element on their own:

```html
<img src="photo.jpg" alt="A description of the photo">
```

# Tags vs Elements

It is worth distinguishing between a **tag** and an **element**: the tag is just the notation (e.g. `<p>`{.html} or `</p>`{.html}), whereas the element is the complete construct. For most elements, this means an opening tag, some content, and a closing tag together. For void elements, such as `<img>`{.html}, the single tag alone constitutes the complete element.

# Nesting Tags

Tags can be placed inside one another — this is called **nesting**. When tags are nested, they must be closed in the reverse order they were opened. For example, if a `<strong>`{.html} tag is opened inside a `<p>`{.html} tag, it must be closed before the `<p>`{.html} is closed:

```html
<p>This is <strong>important</strong> text.</p>
```

# Tag Attributes

Tags can also have **attributes** that provide additional information about the element. Attributes are written inside the opening tag. Most attributes take a value in the form `name="value"`{.html}, but some are **boolean attributes** — their mere presence is enough to activate them, with no value required (e.g. `disabled`{.html}, `checked`{.html}). For example, the `<a>`{.html} tag uses the `href`{.html} attribute to specify the URL of the link:

```html
<a href="https://www.example.com">Visit Example</a>
```
