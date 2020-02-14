# Example Config Route

## [#](#google-firebase) Google Firebase

1.  Make sure you have [firebase-tools](https://www.npmjs.com/package/firebase-tools)installed.

2.  Create `firebase.json` and `.firebaserc` at the root of your project with the following content:

`firebase.json`:

```json
{
  "hosting": {
    "public": "./docs/.vuepress/dist",
    "ignore": []
  }
}
```

`.firebaserc`:

```json
{
  "projects": {
    "default": "<YOUR_FIREBASE_ID>"
  }
}
```

1.  After running `yarn docs:build` or `npm run docs:build`, deploy with the command `firebase deploy`.
