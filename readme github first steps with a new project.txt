1. Anlegen eines Projektes via Web-Browser unter github.com (ohne readme.md usw.)
2. lokal mit dem command-prompt (cmd.exe):
f:
mkdir my-todo
cd my-todo
echo "# my-todo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/bir-thg/my-todo.git
git push -u origin main
