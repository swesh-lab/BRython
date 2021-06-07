# BRython
BRython Test File
* Read Jokes
* Get Quotes
* Append Input Values

<!-- NO INSTALLATION -->
## No Installation

* By including the Brython scripts from a CDN, you can use Brython without installing it locally:

   ```sh
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/brython@3.9/brython.min.js">
    </script>
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/brython@3.9/brython_stdlib.js">
    </script>
   ```
   
   
<!-- DEMO -->
## Demo

   ```sh  
  <html>
  <head>
      <meta charset="utf-8">
      <script type="text/javascript"
          src="https://cdn.jsdelivr.net/npm/brython@3.9.0/brython.min.js">
      </script>
  </head>
  <body onload="brython()">
    <script type="text/python">
      from browser import document
      document <= "Hello BRython!"
    </script>
  </body>
  </html>
  ```
* Save this page as `index.html`. When you open the page, you should see the "Hello BRython!" message displayed on the browser.


<!-- RESOURCE -->
## Resource
[![BRython](https://img.shields.io/badge/BRython-DOCS-blue)](https://brython.info/static_doc/en/intro.html)

