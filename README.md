# AGlassBottle
Android Container Framwork

## 使用容器、组件 模式开发 Android App的想法
* 容器初始化放最先，只设置一个Application
* 容器可注册两种类型的对象：拦截器、组件
* 一个默认拦截器 和 接口，用于向模块注入Application
* 工具类在初始化后就可以依赖容易获取Application了

