# gitci-next

![gitci-next](https://github.com/rjoydip/gitci-next/workflows/gitci-next/badge.svg)

[![Netlify Status](https://api.netlify.com/api/v1/badges/430993dc-7bcc-49f2-af7f-01510c34e091/deploy-status)](https://app.netlify.com/sites/gitci-next/deploys)

Deploying/Hosting `next.js` application in `gh-pages`, `zeit`, `netlify`.

## Secrets

```sh
# ZEIT
ZEIT_TOKEN=<ZEIT_TOKEN>
ZEIT_ORG_ID=<ZEIT_ORG_ID>
ZEIT_PROJECT_ID=<ZEIT_PROJECT_ID>
# Netlify
NETLIFY_AUTH_TOKEN=<NETLIFY_AUTH_TOKEN>
NETLIFY_SITE_ID=<NETLIFY_SITE_ID>
# Github
PERSONAL_GITHUB_TOKEN=<PERSONAL_GITHUB_TOKEN>
USERNAME=<USERNAME>
```

- [Netlify] To get site id go to `state.json` from `.netlify`. If there is no `.netlify` then use `netlify init` to configure project.
- [Zeit] `https://github.com/amondnet/now-deployment#project-linking`
