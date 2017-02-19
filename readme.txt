> Create a new repository on the command line
echo "# makefile" >> README.md
git init
git config user.name <username>
git config user.email <email id>
git remote add origin git@github.com:dhanraju/makefile.git
git add README.md
git commit -m "first commit"
git push -u origin master

> Push an existing repository from the command line
git remote add origin git@github.com:dhanraju/makefile.git
git push -u origin master


To run make files
$ make -f Makefile1
