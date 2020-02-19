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

## [It use Markdown as a Quasar component](#it-use-markdown-as-a-quasar-component)

 QMarkdown is a Quasar component as well as a [Quasar App Extension](https://v1.quasar.dev/app-extensions/introduction).
 If you don't know how to use Markdown or need a refresher,
 this site is recommended: [Markdown Guide](https://www.markdownguide.org/).
 
 ### Interactive Demo
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/demo).

 ### Examples
Can be found [here](https://quasarframework.github.io/quasar-ui-qmarkdown/examples).

 
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


<vue-cmp>
   <q-btn round size="sm" color="accent" @click="clg">
            Click me II
   </q-btn>
</vue-cmp>

### Proudly sponsored by:
   <q-btn round size="sm" color="accent" @click="clg">
            Click me II
   </q-btn>
<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://truelogic.com" target="_blank">
          <img width="300px" src="https://cdn.quasar.dev/sponsors/truelogic.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://campuscloudservices.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/campus-cloud-services.png">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://www.jugglestreet.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/juggle-street.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://comcomservices.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/com-com-services.png">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td align="center" valign="middle">
        <a href="http://www.kalisio.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/kalisio.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://platformpurple.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/platform-purple.png">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td align="center" valign="middle">
        <a href="http://www.bgasoft.com" target="_blank">
          <img width="222px" src="https://cdn.quasar.dev/sponsors/bgasoft.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.letsbutterfly.com/" target="_blank">
          <img width="170px" src="https://cdn.quasar.dev/sponsors/letsbutterfly.png">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://www.projectfinance.io/" target="_blank">
          <img width="222px" height="150px" src="https://cdn.quasar.dev/sponsors/project-finance.png">
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://dreamonkey.com/" target="_blank">
          <img width="222px" height="150px" src="https://cdn.quasar.dev/sponsors/dreamonkey.png">
        </a>
      </td>
    </tr>
    <tr></tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://ib-langenthal.ch/" target="_blank">
          <img width="222px" height="150px" src="https://cdn.quasar.dev/sponsors/ib-langenthal.svg">
        </a>
      </td>
    </tr>
  </tbody>
</table>

