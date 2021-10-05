mkdir repo1
cd repo1
git init
git remote add origin *************

touch 1.txt
echo 111 > 1.txt

git add .
git commit -m "First commit"
git push -u origin master