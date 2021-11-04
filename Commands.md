```bash
# Reference: https://wowchemy.com/docs/hugo-tutorials/deployment/

# preview the website
hugo server --disableFastRender --i18n-warnings

# upload the website's source file to Github
git add .
git commit -m "Commit message"
git push

# generate the website's HTML code into public folder
hugo

# upload the public submodule to Github
cd public
git add .
git commit -m "Commit message"
git push
```