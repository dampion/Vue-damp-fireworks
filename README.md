# vue-damp-firework
The interesting component for Vue developers.
<p align="center"><img src="./public/fireworks.gif" alt="Vue dampion fireworks"></p>

## Contribution Guide

### Installation
```bash
# install packages
yarn add vue-damp-fireworks
or
npm install vue-damp-fireworks
```
### Vue2
```javascript
# global registered in main.js 
import VueFireworks from 'vue-damp-fireworks'
Vue.use(VueFireworks)

# Usage in .vue
<vue-damp-fireworks />
<vue-damp-fireworks :boxHeight="500" :boxWidth="500"/>
<vue-damp-fireworks :boxHeight="500" :boxWidth="500">
    <p>add any element you want</p>
</vue-damp-fireworks>
```

### Component Props

All parameters are optional and fireworks determines the default value of each prop.

| Prop Name       | vue-damp-fireworks Doc & Description                                                     | Type                   | default |
| :-------------- | :--------------------------------------------------------------------------------------- | :--------------------- | :------ |
| boxHeight       | decides the height of the component                                                      | `Number`               | 500     |
| boxWidth        | decides the width of the component                                                       | `Number`               | 500     |
| duration        | decides the duration(ms) of the animation                                                | `Number`               |         |


## Demo Page
[Click me to watch the fireworks](https://dampion.github.io/Vue-damp-fireworks/)

<p align="right">
  <a href="https://www.buymeacoffee.com/dampion" target="_blank" rel="noopener noreferrer">
    <img width="200" src="https://cdn.buymeacoffee.com/buttons/v2/default-green.png" alt="Buy Me A Coffee" />
  </a>
</p>
