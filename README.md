# vue-ui

> UI MODEL

## Build Setup

``` bash
# install ui
npm install vbaseui --save



全局组件使用

可以在项目的入口文件中引入所有组件或所需组件
import VbaseUI from 'vbaseui' // 引入组件库
import '../node_modules/vbaseui/packages/theme-default/lib/index.css' // 引入样式库

Vue.use(VbaseUI)

单个组件按需使用

可以局部注册所需的组件，适用于与其他框架组合使用的场景
import { WButton } from 'vbaseui'

export default {
  components: {
    WButton
  }
}
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
