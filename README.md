# Text to Infinity and Beyond

In the previous lesson's video, Flatiron School founder Avi Flobaum stated that
"the entire web is made of of giant strings of HTML." A "string" as he's using
it here is technologist-speak for a series of letters placed one after another.
A less-technical synonym for this idea is "text."

**The texts sent back and forth on the web are HTML documents**. HTML documents
are strings that contain both _content_ and _markup_. Content looks like: `hi
there` and markup looks like `<p>`. In HTML they are blended together so that
the string `<p>hi there</p>` tells the browser to display the words `hi there`
to the screen in whatever a **p**agraph, according to the browser, looks like.

Here's another fragment of an HTML document:

```html
<h1>About My Poodle</h1>

<p>I have an adorable black poodle named Byron.</p>
```

This document has two "elements" an `<h1>` or "Heading 1" element and a `<p>`
element or "Paragraph" element.

The browser receives, from the server, this HTML document and then uses it to
"draw" a non-markup version in your browser. It drops the HTML elements, but
uses the specification of the _meaning_ of those elements to structure what it
displays on-screen.

**The text sent back and forth on the web are formatted as HTML**. A byproduct of the web being built as a collection of HTML text
(strings) is that we can right-click anywhere on a webpage, select "View Page
Source" and you'll see the HTML that makes up that website. That is true for
any website; there are no exceptions.

Let's peek behind the scenes of two of our favorites websites to see how they
are built. Wikipedia and Google.

**Wikipedia's homepage:**

![](https://curriculum-content.s3.amazonaws.com/web-development/wikipedia.jpeg)


**View source on Wikipedia's homepage:**

![](https://curriculum-content.s3.amazonaws.com/web-development/wikipedia-view-source.jpeg)


**Stackoverflow's top voted questions page:**


![](https://curriculum-content.s3.amazonaws.com/web-development/stackoverflow.jpeg)


**View source on Stackoverflow's top voted questions page:**

![](https://curriculum-content.s3.amazonaws.com/web-development/stackoverflow-viewsource-updated.jpeg)

Much of that will look like gobbledygook, and that's fine for now. The goal of this section is not to become an HTML guru but to understand how HTML is an integral part of the web and know enough HTML to build something functional.

Now peak behind your two favorite websites. Visit them and view their page source. You will see that **behind that product you love are a collection of HTML strings**.

After completing this section, you should have:

- An understanding of the web in a nutshell and its value proposition
- Understand the relationship between the web and HTML
- Know how to construct a properly formatted HTML document
- An understanding of the semantic meaning and use of the key HTML elements
- An understanding of how to decorate elements using CSS
- Given a website image mockup have a sense of how the HTML should be structured 
