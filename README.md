Backbone, Marionette, and Dust.js example====================This demo app is a way for me to test out using Backbone Marionette.js with Dust.js templates. I've thrown in some Bootstrap 3 styles, and I'm using Node.js on the backend, not for serving code but for running the automated stuff below, and because the goal is to eventually integrate the frontend project with a backend one.To launch the web server, open your command window to the directory you've downloaded this project to, and type     node app.jsThere are 2 automated processes included that you'll need to run separately (I open up 2 additional command windows, and leave each one running as I work).You'll need all of the dependencies, which should all be included when you do an install of the project via node, typing     node installThe first is activated by typing (into the command window)     node duster.jsThis  has a duster.config file where you can set the paths to your templates written in plain HTML and Dust, and the output path where you want your compiled templates to go. The defaults are what I am using for my watcher script, which you can run by opening another command window and typing    grunt watchI hope to keep fleshing this project out, as I found out better ways to get things hooked up. I'll probably separate the Marionette stuff into separate files at some point, but for a tiny beginning/learning project it seemed best to leave it all in 1 file.