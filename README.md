# Kyle's Computer

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519_lblunt02

git add .
git commit -m "a comment"
git push origin main
