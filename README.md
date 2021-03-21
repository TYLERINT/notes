# Questions

# 1. How do I ensure that my Jovo voice app can see my google sheets API credentials?

In my _app.js_, I see the follow snippet of code:

`await doc.useServiceAccountAuth(require('./google-sheets-credentials.json')); `

Does this just search the whole project folder for the API credentials?
