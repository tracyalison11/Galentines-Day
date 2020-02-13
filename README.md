# Galentine's Day with Women Who Code DC
Galentine's Day Virtual Cards Project

# Step 1: Download a browser
Google Chrome download: https://www.google.com/chrome/

# Step 2: Download a Code Editor/IDE
Atom - https://atom.io
</br>
Sublime Text - https://www.sublimetext.com
</br>
VS Code - https://www.code.visualstudio.com

# Step 3: Create a Home for your current and future projects
It's easy to forget where you saved a file, especially when you start coding, so let's start by creating a folder on your desktop called `Code`. See below for example:

![Desktop](https://i.imgur.com/yRiofSR.jpg)

Create a new folder inside code and name your project. I am going to call mine `gDay` <3

# Step 4: Create an `index.html` file and save in `Code` folder
Open your new code editor, copy and paste this HTML template code into a new file:
```<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Happy Galentine's Day</title>
</head>

<body>
// Our code is going to go here!
</body>
</html>
```
Save as `index.html` into your new `gDay` folder

# Step 5: Create and save a CSS file called `styles.css` in the same folder as your `index.html` file

[Desktop Folder](https://i.imgur.com/XXgKvwW.jpg)

# Step 6: Reference your CSS file in `index.html` in between the open and closing `<head>` tags. It should look exactly like this:

```
<head>
  <meta charset="utf-8">
  <title>Happy Galentine's Day</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

# Step 7: Let's write our first piece of code!

Add a `header` tag with a celebratory Galentine's day message (e.g. Happy Galentine's Day!) inside the opening and closing `<body>` tags. It should look something like this:

```
<body>
  <h1>Happy Galentine's Day!</<h1>
</body>
```

Read more about header tags here: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements
</br>
Hint: The number after the `h` in the tag corresponds to the size of the header :)

#Step 8: Ensure our code runs in the browser

You can open your `index.html` file in the browser multiple ways. It will vary depending on your code editor. You can right-click on your `index.html` file in the `Code` folder on your desktop and select the option to open in browser. The exact text will vary depend on your operating system. 
</br>
If it's working, you should see your celebratory message in the browser!

# Step 8: Let's write our first CSS rule!

Open up styles.css - it should be empty. The first rule we will write is to change the background color of the webpage using the body tag. In order to write a CSS rule, we need to use a tag or selector to apply the rule to. A body tag CSS rule will look like this:

```body {
    background-color: red;
}
```

You can reference some generic color names like `red`. Developers will most often use hex codes. You can explore different reds here: https://www.colorhexa.com/ff0000
</br>
Using a hex color will look like this:

```body {
    background-color: #ff2b00;
}
```

Refresh your browser to ensure the new rule has been added and is working. If it's not, you may want to check if the file is referenced correctly or try refreshing again!
