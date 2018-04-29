# git terminal commands

*to see your credentials:*
git config user.name
git config user.email

*to config your credentials:*
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

*to clone a repo to desktop (find the clone link on github):*
git clone https://github.com/hanswillem/somerepo.git

*to commit all the changes:*
git commit -a -m "description of the changes"

*to find out what to push (usually origin):*
git remote 

*to push the changes to github:*
git push origin master
