# CircleCI configuration

There are 2 files in this folder, each one for a different use.
The default `config.yml` is used for projects which do not need to be deployed (only semantic releasing to GitHub).
The `webapp.config.yml` is used for web app projects which need to be deployed (using Netlify) & released to GitHub.

For starters the environment variables needed are:
- `GH_TOKEN` for GitHub releases (both files)
- `NETLIFY_STAGING_BUILD_HOOK` and `NETLIFY_PRODUCTION_BUILD_HOOK` for the Netlify builds to be triggered (`webapp.config.yml` only)