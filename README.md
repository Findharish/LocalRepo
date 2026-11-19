<<<<<<< HEAD
HTML stands for Hyper Text Markup Language

-->Html is used to create structure(layouts) of the webpages

-->to create html document we need to use tags

-->tag is the text which is enclosed with in angular brackets.

eg. <tagname> ->opening tag
</tagname> ->closing tag

file-test1.html extension is .html or .htm

<!DOCTYPE html>  - tells to the browser that this is an html5 document doctype is used to represent the version of html to the browser
<html >  - is the root element that wraps all the content on the entire page.
  <head> -  is use to write information about html document such as title, styles, metadata etc
    <title>Demo</title>  -  defines the name shown in the browser tab or windows
  </head>
  <body>  - contains all the visible content that users see on the screen
    Hello World!
  </body>
</html>

<!doctype html>
<html >
  <head>
    <title>Attributes</title>
  </head>
  <body>
    <h1 align="center">Hello world</h1>
    <h1 align="left">Hello world</h1>
    <h1 align="right">hello world</h1>
  </body>
</html>

-->HTML attributes are special words placed within an element's opening tag to provide additional information, configure behavior, or adjust the appearance of that element.

-->HTML heading tags (<h1> to <h6>) are used to define the titles and subtitles on a webpage.

-->Anchor tag is used to create hyper links.

-->Hyper link is also known as "link" or "Hyper Text".

-->Link is the text which contains reference of another webpage.

<a href="https://www.amazon.com" target="_blank" title="Amazon">Click Here</a>

-->target attribute is used to decide where the linked document should be displayed.

--> \_self is the default value, decides display linked doc in same tab.

--> \_blank decides display linked doc in new tab.

## -->Image Tag

--> the <img> tag is used to embed images directly into a webpage.

<img src="./images/1.jpeg" alt="My photo" width="300px" height="250px" />

--> Library
CDN (CONTENT DELIVERY NETWORK) ONLINE LEARNING (GOOD) PRODUCTION(WRONG)
LOCAL OFFLINE

-->HTML tables arrange data into rows and columns using a set of core tags. Here's the basic structure:

<table>
  <thead>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
  </tbody>
  <tfoot>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
  </tfoot>
</table>

| Tag                               | Purpose                                 |
| --------------------------------- | --------------------------------------- |
| `<table>`                         | Defines the table                       |
| `<tr>`                            | Defines a row                           |
| `<th>`                            | Header cell (bold, centered by default) |
| `<td>`                            | Data cell                               |
| `<thead>` / `<tbody>` / `<tfoot>` | Group header, body, and footer rows     |
| `<colgroup>` / `<col>`            | Style columns                           |

Cell merging: use colspan="n" to span columns or rowspan="n" to span rows.

-->Forms

HTML forms are document sections enclosed in the <form> element, designed to collect user input and submit it to a server for processing.
The form tag uses several attributes to manage how user data is gathered, encoded, and transmitted to a server.

attributes-

action: Specifies the URL where form data is sent.

method: Defines the HTTP method (GET or POST) used for submission.

Get(Default):Appends the form data directly to the URL as query parameters.It is responsible to fetch the data from the server.

Post:Sends data securely inside the HTTP request body.

onsubmit: The onsubmit event fires when a <form> is submitted — either by clicking a submit button or pressing Enter in a field. It's the go-to hook for client-side validation before data is sent to the server.
=======
# This is my Local Repo
# this is a new feature
# this is use to pull request
<p> this is new feature dropdown.</p>
<p>this is new feature buttion</p>
>>>>>>> c8c825fad6eb90f4453e3b4714ceb5fe9a985322
