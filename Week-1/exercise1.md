# Pesto Week 1 assignment

Foobar is a Python library for dealing with word pluralization.

## When a user enters an URL in the browser, how does the browser fetch the desired result ?

as we type.

```bash
https://www.pesto.tech/ 
```
or any other URL (Uniform Resource Locator) in any browser. firstly browser goes and looks for it in its cache to find out if that exact website was visited earlier and the IP address is known.
If the URL is not found inside the cache, then the browser will make a DNS request to find the IP Address of the webpage if the DNS doesn't do its job then DNS takes 
the help of the resolver server. The resolver server is nothing but ISP (Internet service provider) resolver returns IP address. 
After getting an IP address, the resolver stores it in its cache so that next time, if the same input comes, it does not have to go to all these steps again. It can now provide an IP address from the cache itself.
so conclusion is 

Clint(browser) makes an HTTP request to the internet then the Web server goes to the database and brings the HTML Page.

## Q a - What is the main functionality of the browser?

  - A web browser's main function is to render and parse HTML,  the group of Tags that are used to design web pages. When a browser loads an HTML file, it brings the HTML, which might contain text, links, images and other items like CSS and JavaScript functions.
 in short, The main function of a browser is to
 Interpret HTML

## Q b - High-Level Components of a browser.
 I - browser includes UI user interface i.e the address bar, back/forward buttons, bookmarks history, etc., that is what you see other than the main window used to display the page you requested.  
II - Rendering engine used to display the requested content, eg, if the requested content is an Html file, it is for parsing Html and CSS and displaying the results.  
III - JS interpreter used to interpret and execute Javascript code.  
 IV - Data storage browser provides complete client-side storage technology.

## Q c - Rendering engine and its use.
The rendering engine displays the requested content. For example, if the requested content is HTML, it parses the HTML and CSS and displays the parsed data in the browser window. 

A rendering engine draws text and images on the screen. The engine draws structured text from a document from HTML, and formats it properly based on the given styles provided in CSS. Examples of layout engines: Blink, Gecko, EdgeHTML, and WebKit.

## Q D - Parsers (HTML, CSS, etc)
The rendering engine displays the requested content. For example, if the requested content is HTML, it parses the HTML and CSS and displays the parsed data in the browser window.  
A rendering engine draws text and images on the screen. The engine draws structured text from a document from HTML, and formats it properly based on the given styles provided in CSS. Examples of layout engines: Blink, Gecko, EdgeHTML, and WebKit.
## Q F - Tree construction
The DOM tree is essentially the tree containing all web HTML elements, whereas the render tree is the top of the DOM and CSSOM trees. The render tree is the one that is actually rendered onto the page.
## Q H - Layout and Painting
   It looks into the elements and figures out where it needs to go on the page. It will see the sizes and position of the elements and try to calculate the line breaks, placement of each of the elements and the relationship between the elements. It already sounds like a lot of work and is a slow process.
   [![domTree.png](https://i.postimg.cc/Z5G2mVrH/domTree.png)]


