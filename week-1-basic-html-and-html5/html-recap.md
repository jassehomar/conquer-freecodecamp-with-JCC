<div style="display: flex; justify-content: space-between; align-items: baseline;">
    <img src="logo.png" width="200px" height="20px">
    <h2 style="text-align: left; text-decoration: none; background: none; border-radius: 0; border: none; box-shadow: none; color: rgba(10, 10, 255, 1); font-size: 18px; font-weight: 800; padding-left: 0; margin-top: 10px;">PROGRAMMING FOUNDATION</h2>
    
</div>
<h1 style="text-align: center; color: rgba(150, 1, 100, 0.8)">Lecture-0 Recap</h1>

# WHAT IS HTML ?
HTML stands for HyperText Markup Language. Its is a markup language for creating webpages and documents. This means we put our content, that should be visible to the browser inside special keywords called **tags**. 

> * _**HyperText**_ means that it uses the HTTP part of the Internet
> * _**Markup**_ means the code you write is annotated with keywords
> * **_Language_** means it can be read by both a human and a computer

## Creating an HTML file

To create an HTML file, take note of below points:

* You don't need any special server or hosting company to write your HTML. But you will probably need a server if you want to publish your html files on the web
* Open the editor of your choice, in our case Visual Studio Code, create a new file and save it as **example.html**
* HTML files end with **.html** extension.
* HTML files run in the browser. That is you open your HTML files with your browser.


## HTML tags

HTML **tags** are the basic building block of any webpage. HTML documents use **tags** to tell the browser how to format our content. Different Tags format the way that information and text is displayed. 

> Note that HTML tags are not displayed in the browser, they are only read by the browser to know what type of content you’ve written.

**TAGS ARE**: 

* Element names surrounded by angle brackets
* They normally come in pairs (start tag and end tag, eg: `<h1>Heading 1</h1>`, `<p>Some Paragraph</p>`), though we have some self closing tags, eg: `<img>`, `<br>`, `<input>`. 
* The end tag is usually the same but with a **forward slash** (/).
* Some tags close themeselves. These tags are called self-closing tags, and basically they don't have any content within them. Eg: `<br/>` or `<br> in HTML5`, `<img>`, `<input>` . Notice that, the slash is after the tag name. But now in HTML5, you don't need to put a slash after the keyword in self closing tags.

### *HTML Tag Attributes*

All html tags can have attributes. Attributes provide information about an element.

* Attributes are placed within the start tag.
* They are formatted as key/value pairs (`id="someId"`).

Examples:

* `<tagname attribute="attributeValue">contant</tagname>`
* `<h1 title="My Company">My Company Name</h1>`

## HTML elements

An HTML ELEMENT is the combination of an opening tag ( eg: `<p>` ), a closing tag ( eg: `</p>` ) and everything in between the opening and closing tags.

```html
Example: 
<p>This is a HTML element and is defined using the paragraph tag</p>
```
This will be ouputted like below in your web browser:

```html
This is a HTML element defined using the paragraph tag.
```

> Remember
> * use a text editor like VSCode to create HTML documents
> * use a browser like Chrome to open HTML documents

## HTML Page Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Page Title</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>I am Omar Jasseh. I live in The Gambia and I am learning how to code at JCC</p>
</body>
</html>
```

## Basic Structure of a Web Page

## !DOCTYPE html
When writing a html document, the first thing to write in our code editor is the doctype declaration, written as `<!DOCTYPE html>`. This provides the web browser with information about the version of HTML in which the page is written in. And `<!DOCTYPE hmtl>` is how we tell our browser that this page is written on HTML5. HTML5 is the latest version of the HTML language.


## html

Immediately after the doctype comes the html element. The **html** element is the root element of the document tree and everything that follows is a descendant of that root element.

> The html element breaks the document into two main sections: the **head** and
the **body**.

## head

The **head** element contains meta data. These are information that describes the document itself, or associates it with related resources, such as scripts and style sheets ( CSS ). The head may contains:

* **title**: The title of the document, shown in a browser's title bar or on the page's tab
* **css**: We normally put CSS codes in the head of our HTML document, either embedded or link from an external file.


## body

The body is where the bulk of the page is contained. Everything that you can see in the browser window (or viewport) is contained inside this element, including paragraphs, lists, links, images, tables, and more.

## p

The p element is one of the most commonly used building blocks of HTML. When you use the **p** element to begin a new paragraph in HTML, it automatically creates some space above and below the content. This space is applied by the browser’s built-in style sheets, but you can override it as you see fit using CSS.

Example

p is used, quite simply, to mark up paragraphs of text:

```html
    
    <p>This is a paragraph of text...</p>
    <p>...and this is another paragraph.</p>

```


## h1
```html
<h1>
</h1>
```

The h1 element is used to indicate the most important (or highest-level) heading on the page.

> In total, we have six heading levels to choose from— h1 to h6 —to add structure to the web page. h1 is the highest heading level (and, by default, the largest in terms of font size) and h6 the lowest (and smallest).

```html
    
    Example
    
    This h1 element is used to present a fluffy welcome message:
    
    <h1>Welcome to JassehCodeCamp Programming Foundation Course</h1>
    
```

## br
```html
    <br/> or <br>
```

The **br** element’s purpose is very simple: it creates a line break within a block of text, leaving no padding or margins between the two blocks of text created by the line break.


## img

```html
<img src="image.png" alt="alternate text" height="" width="" />
```

The img element provides a means for embedding an image in the document.

```html
Example

Here’s an img tag where we specified the required attributes only

<img src="profile-pic.jpg" alt="User Profile Pic"/>
```





<p style="margin-top: 200px">Cheers & Happy Learning,</p>

<p>By Omar Jasseh</p>