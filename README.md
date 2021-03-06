# bootsrap-for-electron

### What is bootsrap-for-electron?

A simple package for building an amazing electron application using bootstrap v4.3.1.

<span>
<img src="https://raw.githubusercontent.com/andreavitiani/bootsrap-for-electron/master/img/bootstrap-logo.jpg" height="100" />
<img src="https://raw.githubusercontent.com/andreavitiani/bootsrap-for-electron/master/img/electron-logo.png" height="100" />
</span>

### Installing

    npm install bootsrap-for-electron

### Getting started

In the head section of your html page, copy/paste the following without changes:<br>

    <link rel="stylesheet" href="node_modules/bootstrap-for-electron/resources/bootstrap.min.css">

In the body section just above the closing body tag of your HTML page, copy/paste the following without changes:

    <script src="node_modules/bootstrap-for-electron/resources/jquery-3.3.1.slim.min.js" ></script>
    <script src=" node_modules/bootstrap-for-electron/resources/popper.min.js" ></script>
    <script src=" node_modules/bootstrap-for-electron/resources/bootstap.min.js" ></script>

You have now linked all the necessary files to use bootstrap on your electron app.

### Reason to install bootstrap via npm

The reason to have bootstrap in local is the usability of your desktop application when the internet connection isn't available.

If you want to use Bootstrap without an npm package in an electron application, you must download the necessary files, copy and paste them into a folder, and copy/paste the correct path into the HTML or template engines file links in case you are using one.

Updating Bootstrap without an npm package is time consuming and error prone because you have to re-upload every single file every time.

**bootsrap-for-electron package** take care of everything without hassle.
