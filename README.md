# Nuxt Turborepo Starter

Nuxt with truborepo setup with opinionated setup

## Features

- Turborepo
- Nuxt ecosystem ready
- Git hooks
- Git Dependabot
- Shared Eslint + Prettier Configuration
- Lintstaged
- Conventional Commits with Commitlint

## System Requirements

- OS: `Linux - Mac - Windows with WDSL 2`
- NodeJS `>=14.0.0`
- NPM: `npm@9.5.0`

## Project setup

Download || clone the repository

```bash
# using ssh
git clone git@github.com:samk-dev/nuxt-turborepo-starter.git
# using https:
git clone https://github.com/samk-dev/nuxt-turborepo-starter.git
```

**this project uses NPM as package manager `node: >=14.0.0` `packageManager: npm@9.5.0`**

## Preparing the repository for development

```bash
# Give husky scripts execution permissions
sudo chmod +x .husky # You'll be prompt to enter you computer password
# Install dependencies
npm install
# if the PREPARE script doesn't run automatically run:
npm run prepare
```

For more information on how to use [Turborepo Documentation](https://turbo.build/repo/docs)
