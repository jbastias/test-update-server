# test-update-server

This is a test update server to be used on Heroku for auto-updates for electron apps

- _uses [nuts](https://github.com/GitbookIO/nuts)_

- it uses a simple electron test app in repo: `jbastias/test-electron-app`

- at the very minimum you must provide the github username, password and the repository (`GITHUB_USERNAME`, `GITHUB_PASSWORD`, `GITHUB_REPO`)


start local server
```
GITHUB_USERNAME=jbastias GITHUB_PASSWORD=***** GITHUB_REPO=jbastias/test-electron-app npm start
 ``
