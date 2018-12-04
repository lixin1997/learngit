Quick setup — if you’ve done this kind of thing before
Use an SSH key and passphrase from account. or git@github.com:lixin1997/learngit.git

Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line

echo "# learngit" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:lixin1997/learngit.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin git@github.com:lixin1997/learngit.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.