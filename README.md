$ mdir ~/Trebol

$cd ~/Trebol

$ git init

$ touch README


$ git add README
# Stages your README file, adding it to the list of files to be committed


$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"


$ git remote add origin https://github.com/genericdesignstudio/Trebol.git
# Creates a remote named "origin" pointing at your GitHub repo


$ git push origin master
# Sends your commits in the "master" branch to GitHub