git remote add upstream https://github.com/cloudflare/cloudflare-docs
git remote -v
git checkout production
git fetch upstream
git merge upstream/production
git push --force origin production
git diff production origin/production
