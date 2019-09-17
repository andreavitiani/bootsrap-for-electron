# bootsrap-for-electron

### What is bootsrap-for-electron?

A simple package for building an amazing electron application using bootstrap.
  
<span align="center">
<img src="img/bootstrap-logo.jpg" height="100" />
<img src="img/electron-logo.png" height="100" />
</span>

### Installing

    npm install bootsrap-for-electron

### Getting started

In the head section of your html page, paste the following:<br>

    <link rel="stylesheet" href="node_modules/bootstrap-it/resources/bootstrap.min.css"><br>

In the body section of the page just above the closing body tag of your HTML page paste the following:

    <script src="node_modules/bootstrap-it/resources/jquery-3.3.1.slim.min.js" ></script>
    <script src=" node_modules/bootstrap-it/resources/popper.min.js" ></script>
    <script src=" node_modules/bootstrap-it/resources/bootstap.min.js" ></script>

You have now linked all the necessary files to use bootstrap on your electron app.

### Reason to install bootstrap via npm

If you want to use Bootstrap in an electron application, you must download the necessary files, copy and paste them into a folder, and copy the correct relative path.

This take time and moreover, this take even more time for updating Bootstrap because you have to re-upload every single file every time. **bootsrap-for-electron** take care of everything for you letting you focus on the core application.

Another aspect is the usability of your desktop application when the internet connection isn't available.
