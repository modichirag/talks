# talks
Collection of my talks built in reveal.js <br>
Slides are hosted at - https://modichirag.github.io/talks/xyz/#/
where xyz is the folder-name

To create a new presentation, the easy steps are - 
- make an empty folder for the new presentation
- copy assets, package.json, gruntfile.js from an exisiting presentation folder
- might as well copy all the html files (index and others) since its easier to edit than create an exisiting presentation 
- do not compy node_modules or reveal.js submodule
- add the submodule from main directory with git submodule add git@github.com:modichirag/reveal.js.git
- edit the .gitmodules file in parent directory to have https address for the submodule
- do git submodule update --init in the presentation folder and its reveal.js submodule
- npm install
- cross fingers, "npm start" to run locally and commit 
