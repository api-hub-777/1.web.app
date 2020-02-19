<div class="q-pa-xl" vue-cmp-wrapper>
 <vue-cmp import="src/components/notes"><notes/></vue-cmp>
</div>  
<div class="row flex-center" vue-cmp-wrapper>
<vue-cmp>
   <q-btn round size="sm" color="accent" class="q-pa-md" @click="clg" >
            Click me I
   </q-btn>
</vue-cmp>
</div>
::: warning

Here are some **services limits** by the `[Spark Plan](https://firebase.google.com/pricing?authuser=0)`.

Thank you for your compassion.

:::
## It use Markdown as a Quasar component

 QMarkdown is a Quasar component as well as a [Quasar App Extension](https://v1.quasar.dev/app-extensions/introduction).
 If you don't know how to use Markdown or need a refresher,
 this site is recommended: [Markdown Guide](https://www.markdownguide.org/).
 
 ### Interactive Demo
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/demo).

 ### Examples
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/examples).


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


<vue-cmp>
   <q-btn round size="sm" color="accent" @click="clg">
            Click me II
   </q-btn>
</vue-cmp>
