# use_effect

## 在函数请求数据
- 没有生命周期
- 配合逻辑和依赖 模拟生命周期

处理副作用
同步致性副作用

主要是用于函数式组件的一次致性

## 使用方法
在 /myscontent/effect.js

- 如果是传空数组那么是 执行一次

- 如果不是空数据 传递的是依赖，
  - 就可以和 state（状态）实现联动
  - 状态更新一次，useEffect 也可以致性一次