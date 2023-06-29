# HTML and the web

## How the web works

The world wide web is a network of computers that can exchange information with each other. There are many different protocols that define the rules on how machines communicate. Browsers use HTTP (Hypertext Transfer Protocol) to communicate with web servers.
<br>

- The URL (Uniform Resource Locator) is the unique address of a resource on the web contains a human readable domain name, that needs to be resolved to the technical IP (Internet Protocol) address of the web server via a DNS (Domain Name Server)
- The browser sends a GET (that's an HTTP method) request to load a HTML (Hyper Text Markup Language) document from a web server
- The web server sends a response containing the document
- Often the HTML code contains references to additional resources (CSS (Cascading Style Sheet) files, images, etc.), which the browser then also requests from the server
- The browser renders the received content to the screen and makes it interactive
- Browsers might also request additional data from servers later via subsequent GET or POST requests
  <br>

## Structuring a website

Developers have two main tools to express a meaningful structure in a website: <br>

1. Using [semantic](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html) HTML elements
2. Nesting of HTML elements
