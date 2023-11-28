> Remember to delete `<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>` in `public/index.html`

```bash
# Reference: https://wowchemy.com/docs/hugo-tutorials/deployment/

# install go

# install hugo: https://gohugo.io/installation/windows/
choco install hugo

# preview the website
hugo server

# upload the website's source file to Github
git add .
git commit -m "Commit message"
git push # GitHub workflow will automatically generate the HTML files and upload them to OSS

# generate the website's HTML code into public folder
hugo
```