git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
mkdir HelloWorld
cd HelloWorld
git init
echo "Hello, World!" > hello.txt
git add hello.txt
git commit -m "Initial commit: Add hello.txt"
git remote add origin https://github.com/username/HelloWorld.git
git push -u origin main
git log
git status
