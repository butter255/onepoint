## 关于缓存

核心模块会自动对 type0 和 type1 进行缓存，且 type0 缓存 5 分钟，type1 缓存 1 天。

**开放接口默认使用缓存，且不具有刷新缓存的作用。**

**文件管理接口不使用缓存，如果需要刷新某个缓存，请调用文件管理接口。**
