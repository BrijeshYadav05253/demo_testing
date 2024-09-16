#Creating a new repository on the command line
touch README.md
git init
git checkout -b main
git add README.md
git commit -m "first commit"
git remote add origin http://localhost:3000/brijesh/demo_testing.git
git push -u origin main

