# nuxt-app-template

This is a basic Nuxt webapp boilerplate. Amongst, obviously starting the folder structure and project in itself, there is also a number of things pre-configured so you can start coding in less than 10 minutes.

It includes:
- CircleCI basic commands, jobs and workflows
- [semantic-releasing](https://github.com/semantic-release/semantic-release)
- Formatting and linting
- Dependabot
- Editorconfig

## Get Started

```bash
# Install dependencies
yarn

# Start development
yarn dev

# Build SPA production app and launch server
yarn build
yarn start

# Generate static app
yarn generate
```

## Using CircleCI config

In the Circle CI config file there are jobs which have 2 variants (build vs generate) which represent SPA and Static, respectively.

These are suffixed by `_generate` and `_build`. You can safely remove the ones you don't intend to use in your project, depending from your architecture.

## Others

Questions regarding Nuxt.js are answered in [its website](https://nuxtjs.org)
