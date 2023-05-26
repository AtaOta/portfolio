# smprotfolio

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
### GIT COMMAND TO PUSH A VUE PROJECT IN GITHUB PAGES
## 1
```sh
 git add dist -f
```
## 2
```sh
git commit -m "adding dist, VERSION-1.0.1"
```

## 3
```sh
git subtree push --prefix dist origin gh-pages
```