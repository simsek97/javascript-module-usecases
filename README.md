# Javascript Module Usecases
In modern javascript development, you will always need different libraries to work together in order to accomplish some certain work. This is basically called *dependency* in modern development world.

However, having different libraries work together brings out some difficulties like conflicting each other. In order to resolve such issues, javascript libraries are encapsulated which is mostly called module.

# History
In a traditional way of Javascript development, dependencies and encapsulation are totally the responsibility of developers. This is mostyl done by loading libraries in a manual order.

This is a simple example of jQuery, Bootstrap page.

```
<!DOCTYPE HTML>
<html dir="ltr" lang="en">
    <head>
        <meta charset="UTF-8">
        <title>My Project</title>
    </head>
	
    <body class="bg-aqua">

        <!-- jquery -->
        <script src="js/jquery/jquery-3.4.0.min.js" type="text/javascript"></script>

        <!-- bootstrap -->
        <script src="js/bootstrap/3.3.6/js/bootstrap.min.js" type="text/javascript"></script>

        <!-- Theme -->
        <script src="theme/js/theme.js" type="text/javascript"></script>
	    
        <!-- Plugins -->
        <script src="theme/js/plugins.js" type="text/javascript"></script>

    </body>
</html>
```
# CommonJS

# Nodejs

# Asynchronous Module Definition (AMD)

## Require.Js

# ES2015

# Babel
