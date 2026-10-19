# vue-pug-stylus-todo-list

A single-page todo application built with Vue 2, Vuex, Pug templates, and Stylus.

## Features

- Add new todo items
- Mark items complete or incomplete
- Archive completed items (move to archived section)
- Active and archived lists displayed separately

## Stack

- Vue 2 with Vuex for state management
- Pug for HTML templating
- Stylus for CSS
- Tachyons utility CSS

## Project structure

```
src/
  App.vue      # root component, todo list UI
  Todo.js      # Todo model
  store.js     # Vuex store (state, getters, mutations)
  main.js      # app entry point
```

## Run locally

```bash
npm install
npm run serve
```

## Build

```bash
npm run build
```
