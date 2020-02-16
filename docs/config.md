<vue-cmp import="src/components/notes"><log-notes page-header-path="my-notes"/></vue-cmp>

<vue-cmp>
   <q-btn round size="sm" color="accent" class="q-pa-md" @click="clg">
            Click me I
   </q-btn>
</vue-cmp>

# Example Config Route v1

## [#](https://console.firebase.google.com) Google Firebase

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
<section>
  <h1>Heading</h1>
  <p>Bunch of awesome content</p>
</section>

1.  After running `yarn docs:build` or `npm run docs:build`, deploy with the command `firebase deploy`.

## My Notes :

<vue-cmp import="src/components/notes"><log-notes page-header-path="my-notes"/></vue-cmp>

<vue-cmp>
   <q-btn round size="sm" color="accent" @click="clg">
            Click me II
   </q-btn>
</vue-cmp>

