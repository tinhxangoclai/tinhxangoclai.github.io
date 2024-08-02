git lfs install

git init

git remote add origin https://github.com/tinhxangoclai/tinhxangoclai.github.io.git

git remote -v
origin  https://github.com/tinhxangoclai/tinhxangoclai.github.io

git checkout main

git add .

git lfs track "*.mp4"

git add .gitattributes

git add file.mp4

git commit -m "add lfs file"
or git commit -m "Add design file"

git push origin main 