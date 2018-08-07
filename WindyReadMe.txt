2918 August 03
I started Brad’s Git a Web Developer Job - Workflow once again.
I started from Git your hands dirty.

1. Brad goes on to GitHub and sets up a blank (travel-site) repo without a repo.  This  is because we already set one up locally on step.

2. He the clones a repo (travel-site-files)  and changes local folder name to travel-site

3.  I need to push this to GitHub. But, because I cloned for Brad’s travel-site-files it will push back there.  Check the path git remote -v

4. To set path: git remote set-url https://github.com/jazzrail/travel-site.git

5. git push origin master


NPM
npm install just installs the package.  npm install —save puts a record in the Json file.  Once this list is in place, running npm install again installs all the stuff listed in the Json file.

GULP
VIP!   When following Brad’s tutorial, the json file already had Gulp files and gulp is laready installed on my computer. I need to stick to these, so ignore when he says npm install npm install gulp-cli —global .  The first time I tried to install gulp I had to run: sudo npm install npm install gulp-cli —global  

#1. Run gulp (return) It will say no gulpfile found. This is good, as it shows we have gulp, just no files yet. Run gulp -v and I will see I have a version installed.

#2 I don’t need to do this as gulp already in the travel-site folder