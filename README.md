# talks
Collection of my talks built in reveal.js <br>
Slides are hosted at - https://modichirag.github.io/talks/xyz/#/
where xyz is the folder-name

To create a new presentation, the easy steps are - 
- make an empty folder for the new presentation
- copy assets, package.json, gruntfile.js from an exisiting presentation folder
- might as well copy all the html files (index and others) since its easier to edit than create an exisiting presentation 
- do not copy node_modules or reveal.js submodule
- add the submodule from main directory with git submodule add git@github.com:modichirag/reveal.js.git
- edit the .gitmodules file in parent directory to have https address for the submodule
- do git submodule update --init in the presentation folder and its reveal.js submodule
- npm install
- cross fingers, "npm start" to run locally and commit 

It is possible npm install fails with ERR code 1
This might happen due to old package.json and new version of npm
To resolve this error, you need to upgrade the dependency module that causes the error.
Then follow the following steps:
# check your package.json for dependency updates
npx npm-check-updates
# 👇 write newer version in package.json
npx npm-check-updates -u
# 👇 install the latest version
npm install
