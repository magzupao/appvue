# appvue

Servidor de prueba:
- Debian 10
- node v16.19.0
- npm 9.3.0
- @vue/cli 5.0.8


## Creamos proyecto VUE
```
mkdir appvue
cd appvue
vue create appvue

#respondemos las siguientes acciones, marcadas con X y en algunas opciones con Y o N:
Vue CLI v5.0.8	
? Please pick a preset:
  proyectobase ([Vue 3] babel, eslint)
  proyecto01 ([Vue 3] babel, typescript, vuex, eslint)
  Default ([Vue 3] babel, eslint)
  Default ([Vue 2] babel, eslint)
X Manually select features

Vue CLI v5.0.8
? Please pick a preset: Manually select features
? Check the features needed for your project: (Press <space> to select, <a> to toggle all, <i> to invert selection, and <enter> to proceed)
 X Babel
 X TypeScript
 ◯ Progressive Web App (PWA) Support
 ◯ Router
 ◯ Vuex
 ◯ CSS Pre-processors
 ◯ Linter / Formatter
 ◯ Unit Testing
 ◯ E2E Testing

Vue CLI v5.0.8
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, TS
? Choose a version of Vue.js that you want to start the project with
  3.x
X 2.x

Vue CLI v5.0.8
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, TS
? Choose a version of Vue.js that you want to start the project with 2.x
? Use class-style component syntax? Yes
? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? Yes
? Where do you prefer placing config for Babel, ESLint, etc.?
  In dedicated config files
X In package.json

Vue CLI v5.0.8
? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, TS
? Choose a version of Vue.js that you want to start the project with 2.x
? Use class-style component syntax? Yes
? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? Yes
? Where do you prefer placing config for Babel, ESLint, etc.? In package.json
? Save this as a preset for future projects? (y/N) N

```



## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
