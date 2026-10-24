git checkout main
git commit -a -m update
git push
git checkout pr
git pull origin main
git commit -a -m update2
git push
git checkout main
