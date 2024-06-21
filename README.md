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

### elemnts without any closing tags (void elemnts) 

img : image, having attributs as src: source/location alt: text description width: width of image in pixels height: in pixels 

### boolean attributes 

< input type="text" disabled="disabled" />  form element that that cant make entries.

### single or double quotes

href='' and href="" both are acceptable

### using quotes inside a quote

title=" An &quote ; Interesting &quote ; Reference ". just type & and end with ; having quote written in between.

### hyperlinks

a : basic link, should have href="link" attribute.

block level links can be created by wraping the content inside a an anchor element.
title="" attribute adds title to your links (when you hover).

**same directory link** have href as "contact.html" or "aboout.html"

**moving into subdirectories** work having href as "projects/index.html"

**moving up into parent directories** work having href as "../pdf/project/product.html".
use .. to move up a directory.

### Document fragments

(referance to a part in the same page)
you can move into the same document using links, just add the id="" to that heading and then link it using href. 

### Absolute vs Relative URLs

**absolute url**  points to a location defined by its absolute path. https: // www. example. com/ projects/ index. html

**relative url** points to a location that is relative to that file you are currently in. href="product.pdf" if that index is in the same folder with the product.pdf 

### Email links

a with href="mainto:###", ###=email of the recipient. a new outgoing email window will be opened by the user's email client with ### as destination, if ### is not present then it will open without any destination address. **specifying details** (you can add other information like subject, cc and body too)

