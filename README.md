create a new repository on the command line

  echo "# demo-1" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/benjanson/demo-1.git
  git push -u origin master


Push an existing repository from the command line

  git remote add origin https://github.com/benjanson/demo-1.git
  git push -u origin master
