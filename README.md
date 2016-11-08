# test-update-server

This is a test update server to be used on Heroku for auto-updates for electron apps

- _uses [nuts](https://github.com/GitbookIO/nuts)_

- it uses a simple electron test app in repo: `jbastias/test-electron-app`

- at the very minimum you must provide the github token and the repository (`GITHUB_TOKEN`, `GITHUB_REPO`) or (`GITHUB_USERNAME`, `GITHUB_PASSWORD`, `GITHUB_REPO`)

- [create token](https://github.com/blog/1509-personal-api-tokens) (ask me for the token).

start local server

```
GITHUB_TOKEN=**** GITHUB_REPO=jbastias/test-electron-app npm start

or

GITHUB_USERNAME=jbastias GITHUB_PASSWORD=***** GITHUB_REPO=jbastias/test-electron-app npm start
```