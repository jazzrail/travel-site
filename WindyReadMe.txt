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