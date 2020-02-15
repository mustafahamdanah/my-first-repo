## INTRODUCTION

### The Structure of This Book :
- Html
- Css
- Practical

### How People Access the Web :
* Browsers :
 > People access websites using software called a web browser.
Popular examples include Firefox, Internet Explorer, Safari,
* Web Servers :
 > When you ask your browser for a web page, the request is sent
  across the Internet to a special computer known as a web server which hosts the website.
* Screen readers :
> Screen readers are programs that read out the contents of a computer screen to a user. They
are commonly used by people with visual impairments.

### How Websites Are Created :
- All websites use HTML and CSS, but content management systems, blogging software, and
e-commerce platforms often add a few more technologies into the mix.

### How the Web Works :
- When you visit a website, the web server hosting that site could be anywhere in the
world. In order for you to find the location of the web server, your browser will first connect
to a Domain Name System (DNS) server.

## Structure 

* In all kinds of documents, structure is very important in helping readers to understand the messages you are 
trying to convey and to navigate around the document. So, in order to learn how to write web pages, 
it is very important to understand how to structure documents. In this chapter you will:

> See how HTML describes the structure of a web page

> Learn how tags or elements are added to your document

### HTML Describes the Structure of Pages
         <html>
         <body> </body>
         <p> </p>

- The HTML code is made up of characters that live inside angled brackets — these are called HTML elements. 
Elements are usually made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser something about the information 
that sits between its opening and closing tags.

### HTML Uses Elements to Describe the Structure of Pages

- Tags act like containers. They tell you something about the information that lies
between their opening and closing tags.

      - The opening <html> tag indicates that anything between it and a closing </html> tag is HTML code
      - The <body> tag indicates that anything between it and the closing
        </body> tag should be shown inside the main browser window.
      - Words between <h1> and </h1> are a main heading.
      - A paragraph of text appears between these <p> and </p> tags.
      - Words between <h2> and </h2> form a sub-heading.
      - Here is another paragraph between opening <p> and closing </p> tags.
      - Another sub-heading inside <h2> and </h2> tags.
      - Another paragraph inside <p> and </p> tags.
      - The closing </body> tag indicates the end of what should appear in the main browser window.
      - The closing </html> tag indicates that it is the end of the HTML code.
      - <body> You met the element in the first example we created. Everything inside this element is
        shown inside the main browser window.
      - <head> Before the <body> element you will often see a <head> element. This contains information
        about the page (rather than information that is shown within the main part of the browser
        window that is highlighted in blue on the opposite page). You will usually find a <title>
        element inside the <head> element.
      - <title> The contents of the <title> element are either shown in the top of the browser, above where
        you usually type in the URL of the page you want to visit, or on the tab for that page (if your
        browser uses tabs to allow you to view multiple pages at the same time).

   
#### Attributes Tell Us More About Elements :
       Attributes provide additional information about the contents of an element.
                   <p lang="en-us">Paragraph in English</p>
                   







