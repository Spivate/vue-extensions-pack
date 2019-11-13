# Vue Extensions Pack

Extensions pack for vue development.

## Recommended-Settings

We don't recommend to setup `user` settings, because you may have different projects which has different code style.

So you'd better to setup `workspace` settings for a certain project.

Edit the `settings.json` file of `workspace`:

```json
{
  "files.eol": "\n",
  "eslint.autoFixOnSave": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    {
      "language": "vue",
      "autoFix": true
    },
  ]
}
```

Edit the `.eslintrc.js` file of your project:

```JavaScript
module.exports = {
  // ...
  extends: [
    'plugin:vue/essential',
    'plugin:vue/strongly-recommended',
    'plugin:vue/recommended',
    '@vue/airbnb',
  ],
  // ...
};
```

## Extensions Included in this pack

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.
* [vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) - Vue tooling for VSCode
* [vue-peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek) - Allows peek and goto definition for Vue single-file components
* [vuex peek](https://marketplace.visualstudio.com/items?itemName=Mcbai.vscode-vuex-peek) - Allows peek and goto vuex definition for Vue components
* [Vue CSS Peek](https://marketplace.visualstudio.com/items?itemName=CharlesWu.vue-css-peek) - 为单页面的vue文件提供css转定义的支持
* [auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text
* [Path IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames
* [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) - npm support for VS Code
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) - highlight TODOs, FIXMEs, and any keywords, annotations...
* [Template Generator](https://marketplace.visualstudio.com/items?itemName=DengSir.template-generator-vscode) - Files/Folders template for vscode
* [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Supercharge the Git capabilities built into Visual Studio Code — Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more
