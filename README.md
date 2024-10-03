# train-revision

echo "# train-revision" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/geofLegrand/train-revision.git
git push -u origin main