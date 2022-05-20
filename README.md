# aws-cloudops-security

### Setup:

#### Install Hugo:

On a mac:

`brew install hugo`

On Linux:

- Download from the releases page: https://github.com/gohugoio/hugo/releases/tag/v0.37
- Extract and save the executable to `/usr/local/bin`

On Windows:

- Get a Mac

#### Clone this repo:

From wherever you checkout repos:
`git clone https:/github.com/dixonaws/aws-cloudops-security`

#### Install node packages:

`npm install`

#### Run Hugo locally:

`npm run server`
or
`npm run test` to see stubbed in draft pages.

#### View Hugo locally:

Visit http://localhost:8080/ to see the site.

#### Making Edits:

As you save edits to a page, the site will live-reload to show your changes.

#### Building the site
```npm run build``` generates the production site in the public/ folder.

You can use this in Amplify:

```yaml
version: 1
frontend:
phases:
preBuild:
commands:
  - npm ci
build:
commands:
  - npm run build
artifacts:
# IMPORTANT - Please verify your build output directory
baseDirectory: /public
files:
  - '**/*'
cache:
paths:
  - node_modules/**/*
```