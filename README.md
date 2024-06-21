# Basic_HTML_Practice


HTML (HyperText Markup Language) is a markup language that tells the browser how to structure the web pages.

## 1. HTML head

The head part is not displayed but is there to contain information as page title, links, and other metadata.

Web browsers use information about contained in the head to display the web page correctly.

The **metadata** element describes data within the web page. for example < meta charset="utf-8"/ > tells the browers to follow the utf-8 character encoding.
Here meta is an element and charset is an attribute of that element. meta element includes **name** and **content** attributes. name specifies the type of element or information it contains and content specifies the actual meta content

The **title** element represents the title of the overall document.

The contents of the **body** are displayed on the web page. 

The **h1** to **h6** are used to display title within your page.

**p** element contains the paragraph.

## 2. HTML body

**This is where we introduce CSS**

There are many ways to include css into your html:
- **External CSS** is to make a style.css file and then make a link in your html head to that css file
< link rel="stylesheet" href="style.css" />
- **Internal CSS** define css directly into your html head, just add < style > --your css-- < / style >
- **Inline CSS** is to add css into individual HTML elements using style attribute. just do < p style="color: blue;" > ---your para--- < /p >

### not some basic tags

div : block-level element : used to make sections or groupings in a web page

span : inline element : small scale styling 

### some basic tags 

h1 to h6 : heading

p : paragraph

ul : unordered list

ol : ordered list 

li : list item

em : emphasis

strong : strong importance

b : bold / i : italic / u : underline 

### hyperlinks

a : basic link, should have href="link" attribute

