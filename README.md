# merge-conflict-demo
git clone <repo_url>
cd merge-conflict-demo
git checkout -b update-readme
echo "Papildināta informācija atzarā update-readme." >> README.md
git add .
git commit -m "Rediģēts readme fails"
git push origin update-readme
