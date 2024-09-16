#Creating a new repository on the command line
touch README.md
git init
git checkout -b main
git add README.md
git commit -m "first commit"
git remote add origin http://localhost:3000/brijesh/demo_testing.git
git push -u origin main


#mirror testing

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/BrijeshYadav05253/demo_testing.git
git push -u origin main
