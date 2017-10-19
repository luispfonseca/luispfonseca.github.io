# luispfonseca.github.io

Personal webpage. Link: http://luispfonseca.com

Code to run local version of webpage for testing:

Guide for page building: https://programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages#what-are-static-sites-jekyll-etc--why-might-i-care-

## Cheatsheet <a id="section8"></a>

**To test stuff locally** (new plugin, theme, how a new blog post looks):

* *Start local site*: Type `bundle exec jekyll serve --watch` at the command line
* *Visit local site*: Open **localhost:4000/yourwebfoldername/** in a web browser (e.g. *localhost:4000/JekyllDemo/*). Don't forget the trailing slash!
* *See changes on the local site as you make them:* While the site is running, after making changes to website files: save the files and refresh the webpage to see the changes—**except for the _config.yml file**, for which you must stop running the website and restart running the website to see changes.
* *Stop local site:* Hit **control-c** on the command line.

**To move local changes to your live site** (new post, settings tweak, etc.):

* Make the desired changes to your website's local files.
* Open the GitHub Desktop app, make sure your website is chosen in the left sidebar's list of repositories, and write your commit message summary (and description if desired).
* Click "Commit to gh-pages" in the lower left.
* After the commit has completed, click "Sync" in the upper right.
* Allow 10-90 seconds for your changes to reach GitHub's web servers, then visit your website and refresh the page to see your changes live.