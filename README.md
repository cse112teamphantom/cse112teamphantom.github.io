# cse112teamphantom.github.io
Team Phantom Website

To start contributing, do the following:
mkdir team_website
cd team_website
git remote -v
git remote remove origin
git remote add origin url
git pull origin master --allow-unrelated-histories

Next, whenever you make changes to file and want to merge with everything we have:
git add .
git commit -m "some message of what you did"
git push origin master
