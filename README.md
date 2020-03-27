# webapps-express
 
 Part 1:
 While viewing the app in a browser, go to the route "/yourname". What happens?
 The file is not found

 Why do we use backticks for the log string(instead of single or double quotes)?
It is used for expressions of literals.

Look in package.json. What does the start of script call? What folder is it looking in? What is the name of the file? Look in this file - what is the default port number?
start script is called /bin/www
It is looking in the bin folder
The name of the file is www
default port is 3000

Access your app at localhost:3000 in your browser. What do you see?
Express 
Welcome to Express

Where is package.json? What are the routes? Where are the views? What is .gitignore? What's in the node_modules folder? Can you find any HTML? CSS? JavaScript? Images?
package.json is in the project folder
The views are in the view folder
.gitignore is used tells what files gitHub should ignore
there is no HTML files but CSS, JavaScript, and Images are in the public folder

Look up the Pug view engine. What did it use to be called? Which is more popular?
pug use to be jade. Pug is now more popular because it is more updated.

What file needs to be changed to update the page to say "I love Express"?
index.jade

What file needs to be changed to update the page to set the title to "Disneyland" so the paragraph reads "I love Disneyland"?
routes/index.js and index.jade