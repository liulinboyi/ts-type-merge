## 缘由
最近遇到要对一些第三方包进行类型扩展，经过搜索，整合了一下。
## 介绍
例如为`buffer-detect`添加`uuid`属性，就可以这样使用：
在ts项目中添加`shims.d.ts`文件
```typescript
import 'buffer-detect'


declare module 'buffer-detect' {
  export interface bufferDetect {
    uuid?: string
  }
}
```
## 仓库
[https://github.com/liulinboyi/ts-type-merge](https://github.com/liulinboyi/ts-type-merge)
## 引用
[https://segmentfault.com/a/1190000022842783](https://segmentfault.com/a/1190000022842783)
[https://zhuanlan.zhihu.com/p/367770649](https://zhuanlan.zhihu.com/p/367770649)
[https://blog.csdn.net/palmer_kai/article/details/107687717](https://blog.csdn.net/palmer_kai/article/details/107687717)

