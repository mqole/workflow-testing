git commit -a -m update
git push
git checkout pr
git merge main --commit -s recursive theirs
git push
git checkout main
