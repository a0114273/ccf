# Part 1

## HTML

1. Create a new file and save it with the extension .html. The computer is really smart and when you save a file with ".html", it knows what to do with that "html"
2. Try opening this new file on internet browser (Chrome, IE etc)
3. Now add a header with a creative title for your page. When you add a <head> tag in HTML you can add a `<title>` tag within the head. This will then use this title for the top of the browser window. 
Remember to save your file. Everytime, you make a change, save your file. 
4. Now add a `<body>` below the `<head>`. 
5. Add `<h1>, <h2>, <h3>, <h4>, <h5>, <p>` tags inside the body and type "Cambodia" and see how the font size changes. 
6. Pick the font size that suits you the best and delete the rest. 
7. Now, let us give this tag an "id=name" (like an identification name) so that we can call it anywhere. 
8. Save your file and see that adding the id does not impact the webpage. 
9. Add empty links to other exercises by using `<a>`.
  
## CSS

1. Beautify this page by adding style to our body. By adding this, we will be able to control the look and feel of the page how ever we want.
2. Each section of body can be divided into divisions or `<div>` and can be styled separately. Enclose different parts of the webpage inside `<div>` and style them differently. (color, background-color, align, font) 
3. Open your browser console and play around with the styles to see what your page will look like then go ahead and make those changes in your file.
  
## JavaScript

1. Moving on to some even more exciting part, let us now let us try and make the computer ask us what our name is.
2. Notice the "script" after Java? That is the next tag we will work with. Add `<script>` tag in the `<body>`section and add `prompt("What is your name?", "ABC XYZ");`
3. Save your file and see what happens when you open this file on your browser. 
4. Now, let us make the computer remember our name by saving our name. Just add the following, and your name will be saved in the variable "name". `var name = prompt("What is your name?", "ABC XYZ");`	
5. Now, add the following and it will display your name in the body. `document.getElementById("name").innerHTML = "Hello " + name;`

What does this line do? It tells the name ID that we made earlier to change its name from "Cambodia" to what you print when the computer asks you "What is your name?"  		 		
