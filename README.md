# WordCamp Atlanta 2020 Theme

Based on Gulp Boilerplate. https://github.com/cferdinandi/gulp-boilerplate

## Instructions

This is a theme for the WordCamp Atlanta 2020 site. It is intended to be used with the Remote CSS feature outlined here:

https://make.wordpress.org/community/2015/11/24/remote-css-plugin-launched-on-wordcamp-org/

### Local Development

1. Install VVV: https://github.com/WordPress/meta-environment
2. Activate the WordPress meta-environment. More info here: https://github.com/WordPress/meta-environment
3. Install Campsite 2017 theme to the WordCamp multisite. https://github.com/2ndkauboy/campsite-2017
4. Deploy this repo as a child theme for Campsite 2017.
5. Run `npm i` in the theme folder.
6. Run `gulp watch` to compile sass and compress images.
7. Optional - If you want to match the content from the live site, you can run `wp site empty` to clear out the local site, then export an XML from the live site and import the XML into local.

### Deployment

1. Make sure it's not a Friday.
2. Make sure all compressed mages have been uploaded to the live site first, and make sure any image references in CSS point directly to the image's URI on the live site.
3. Push to master branch. Remote CSS will pull from here via GitHub API.
4. Double-check to make sure everything looks OK.


