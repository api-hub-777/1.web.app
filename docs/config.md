
## Config :

::: warning

Here are some **services limits** by the **firebase -** [Spark Plan](https://firebase.google.com/pricing?authuser=0)**.**

***Thank you for your compassion.***

:::

## It use Markdown as a Quasar component with Quasar's primitives

 QMarkdown is a Quasar component as well as a [Quasar App Extension](https://v1.quasar.dev/app-extensions/introduction).
 If you don't know how to use Markdown or need a refresher,
 this site is recommended: [Markdown Guide](https://www.markdownguide.org/).
 
### Interactive Demo
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/demo).

### Examples
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/examples).

### The Quasar component sample: 
<div class="fit row flex-center" vue-cmp-wrapper>
 <vue-cmp>
    <q-btn  class="q-pa-sm" rounded size="lg" color="accent" @click="clg">
             Click me II
    </q-btn>
 </vue-cmp>
</div>

### Style :

 [ Prism ](https://prismjs.com)

## Installation :

### [Google Firebase](https://console.firebase.google.com)


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
    "default": "‹YOUR_FIREBASE_ID›"
  }
}
```
