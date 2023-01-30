# 什么是vuex？
vuex是一个专门为vue设计的状态管理工具，它采用集中式存储管理应用的所有组件的状态，并以相应的规则保证状态以一种可预测的方式发生变化。
就是说vuex是一个专门给vue设计管理状态的工具，他会把一些状态集中存储在某一个地方，并且对状态管理提供了管理规则，保障了状态的改变是可预测的。

可以理解vuex是一个全局变量，并且他里面的状态适配了vue的响应式规则

# 使用方式
1、引入vuex
2、通过vue.use() 注册vuex插件
3、实例化store仓库 new Vuex.Store(选项)
4、抛出store
5、在根实例出引入实例的store，给根实例添加store选项

vuex的选项：
state 存储状态
mutations 改变状态的函数
actions 异步逻辑的处理
modules 划分不同的状态模块

```
import Vue from 'vue'
import Vuex from 'vuex'

Vue.use(Vuex)

export default new Vuex.Store({
  state: {
  },
  getters: {
  },
  mutations: {
  },
  actions: {
  },
  modules: {
  }
})
```

如果我们有1000个页面，其中500个页面都应用到了vuex中的这个状态，如果有其中200个页面都需要修改状态，突然状态报错了，为了保障状态以可预测的行为修改状态，vuex规定状态的修改只能在mutations中进行修改