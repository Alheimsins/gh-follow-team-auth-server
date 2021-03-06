[![Build Status](https://travis-ci.com/Alheimsins/gh-follow-team-auth-server.svg?branch=master)](https://travis-ci.com/Alheimsins/gh-follow-team-auth-server)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

# gh-follow-team-auth-server

Auth server for gh-follow-team.

Developed for running serverless at [Vercel](https://vercel.com) 

## Setup

Create an OAuth app on GitHub.

Set Authorization callback URL to `<url-for-this-app>/callback`

Add clientID and clientSecret as `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` to your Vercel project

## API

### /login

Redirects to GitHub for authorize

### /callback

The callback for OAuth  authorization

## Development

Add secrets to a local `.env``

Start the server with the [vercel-cli](https://vercel.com/download)

```
$ vc dev
```

## Releated

- [gh-follow-team](https://github.com/Alheimsins/gh-follow-team) cli for following team members

# License

[MIT](LICENSE)

## About

Created with ❤ for [Alheimsins](https://alheimsins.net)

<img src="https://image.ibb.co/dPH08G/logo_black.png" alt="Alheimsins logo" height="150px" width="150px" />
