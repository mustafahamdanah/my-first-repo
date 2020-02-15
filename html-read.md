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
                   
## HTML5 

In HTML5, web page authors do not need to close all tags, and new elements and attributes will
be introduced. At the time of writing, the HTML5 specification had not been completed, but
the major browser makers had started to implement many of the new features, and web page
authors were rapidly adopting the new markup. Despite the fact that HTML5
is not yet completed, you can safely take advantage of the new features of the language as
long as you endeavour to ensure that users with older browsers will be able to view your pages
(even though some of the extra features will not be visible to them).

#### DOCTYPEs

- Because there have been several versions of HTML, each web page should begin with a
DOCTYPE declaration to tell a browser which version of HTML the page is using
                 
                   <!DOCTYPE html>
                   use in HTML5
                   
#### Comments in HTML
- If you want to add a comment to your code that will not be
visible in the user's browser, you can add the text between these characters:

                    <!-- comment goes here -->
         
#### ID Attribute
- Every HTML element can carry the id attribute. It is used to
uniquely identify that element from other elements on the page

                    <p id="pullquote"> </p>
                     
#### Class Attribute
- Every HTML element can also carry a class attribute. Sometimes, rather than uniquely
identifying one element within a document, you will want a way to identify several elements
as being different from the other elements on the page. 

                   <p class="important"> </p>

#### Block Elements
- Some elements will always appear to start on a new line in
the browser window. These are known as block level elements.
- Examples of block elements are

                    <h1>, <p>, <ul>, and <li>.
                    
#### Inline Elements
- Some elements will always appear to continue on the same line as their neighbouring
elements. These are known as inline elements
- Examples of inline elements are
                    
                   <a>, <b>, <em>, and <img>.
                    
#### Grouping Text & Elements In a Block
                   
                   <div> </div>

- The element allows you to group a set of elements together in one block-level box.

#### Grouping Text & Elements Inline

                  <span> </span>

- The span element acts like an inline equivalent of the div
element. It is used to either:

1. Contain a section of text where there is no other suitable
element to differentiate it from its surrounding text
2. Contain a number of inline elements The most common reason why
people use span elements is so that they can control the
appearance of the content of these elements using CSS.

#### IFrames

                  <iframe> </iframe>
                  
- An iframe is like a little window that has been cut into your
page — and in that window you can see another page. The term
iframe is an abbreviation of inline frame
An iframe is created using the iframe element. There are a
few attributes that you will need to know to use it:
- src
The src attribute specifies the URL of the page to show in the frame.
- height
The height attribute specifies the height of the iframe in pixels.
- width
The width attribute specifies the width of the iframe in pixels.

#### Information About Your Pages

                  <meta> 
                  
- The meta element lives inside the head element and contains information about that
web page. It is not visible to users but fulfills a number of purposes such as telling 
search engines about your page, who created it, and whether or not it is time sensitive                  

## HTML5 Layout 

### New Html5 Layout Elements

#### Headers & Footers
                 
                 <header> <footer>
                 
The header and footer elements can be used for:
-  The main header or footer that appears at the top or
bottom of every page on the site.
-  A header or footer for an individual article or
section within the page.

#### Navigation 

                <nav> </nav>
            
- The nav element is used to contain the major navigational
blocks on the site such as the primary site navigation.

#### Articles

               <article> </article>

- The <article> element acts as a container for any section of a
page that could stand alone and potentially be syndicated.
This could be an individual article or blog entry, a comment
or forum post, or any other independent piece of content
 
#### Aside

               <aside> </aside>

- The aside element has two purposes, depending on whether it is inside an article
element or not. When the aside element is used inside an article
element, it should contain information that is related to the
article but not essential to its overall meaning. 

#### Sections

              <section> </section>

- The section element groups related content together, and
typically each section would have its own heading

#### Heading Groups

              <hgroup> </hgroup>
              
- The purpose of the hgroup element is to group together a set of one or more h1 
through h6 elements so that they are treated as one single heading. 

#### Figures

              <figure> <figcaption>

- You already met the figure element in Chapter 5 when we
looked at images. It can be used to contain any content that is
referenced from the main flow of an article (not just images)
- Examples of usage include:
   - Images
   - Videos
   - Graphs
   - Diagrams
- The figure element should also contain a figcaption element which provides a text
decription for the content of the figure element.

#### Sectioning Elements

             <div> </div>
             
-  the div element will remain an important way to group together related elements,
because you should not be using these new elements that you have just met for purposes other
than those explicitly stated. Where there is no suitable element to group a set of
elements, the div element will still be used             

#### Linking Around Block-Level Elements

- HTML5 allows web page authors to place an -a- element around
a block level element that contains child elements. This
allows you to turn an entire block into a link.







