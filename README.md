git config --global user.name "Agri Kuswandanir"
git config --global user.email agrikuswandani@gmail.com

mkdir webrtc
cd public
git init
touch README
git add README
git commit -m 'first commit'
git remote add origin https://github.com/agri95/webrtc.git
git push -u origin master
