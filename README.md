familyhistorydatabase
=====================

Current Public version of the familyhistorydatabase.

Getting Started (after forking/cloning the repo)
================================================
1. Make sure you have Node.js installed on your machine.
2. Once node.js is installed run `npm -v` to assure it is installed
3. With npm run these two commands:
`npm install grunt-cli -g`
`npm install bower -g`
4. Install Ruby
5. Install Compass (after checking to make sure ruby is installed run `gem update --system` and then `gem install compass`)
6. Make sure all of the steps above are complete by checking versions
7. Once they've all been installed, move to the `familyhistorydatabase/client/familyhistorydatabase/` folder and run `npm install` and then `bower install`
8. If those were done correctly, you should be able to run a build -> `grunt build` without any errors.
9. Currently the index page is a '.php' file. You can change this back to a .html file, and remove the php code to test it on a localhost node.js server. ( you do this by running the command `grunt serve` )
