##README##


##Jumpstart - V1.1.0##

Developed by Jeffrey Scott French with modified assets from:
* iotacss - scss framework
* Gulp for Wordpress - gulp workflow by Ahmad Awais

License: MIT or as noted by original authors.




###Installation Notes:###


####Clone this repo:####
* git clone <this-repo> <new-name>
* change to the new directory from above
* create new repo on github for this project (same name as above)
* git remote set-url origin <new-repo-on-github>
* git push origin master <new-repo-on-github>

Update package.json and README with project info

####Install Node Modules:####
npm install - this installs all dev dependencies from package.json and the iotacss node modules, but does not overwrite the iotacss folders in build/assets/scss.


####Iotacss - (optional) install latest version using iotaplate:####
* Navigate to build/assets/scss in the CLI and run "iotaplate" to re-generate with latest updates. ** This will overwrite any customization in iotacss contained in the Jumpstart package.
* change main.scss to \_iota_main.scss to be imported into styles.scss
* follow docs for changing settings: https://www.iotacss.com/docs/settings/


####Search/Replace (case sensitive please!) these placeholders in your project folder, examples given:####
ProjectName          --> The Bitter Bottle
ProjectURLBase       --> thebitterbottle
ProjectAcronym       --> tbb (used for some css selectors)
url-social-mail      --> mailto:thebitterbottle@gmail.com (or link contact form)
url-social-facebook  --> https://facebook.com/thebitterbottle
url-social-instagram --> https://instagram.com/thebitterbottle


####Responsive Images Partials:####
Don't worry about the sizes attributes until you get to the end of development and can see how your layouts are dictating your image usage.