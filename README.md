TypeScript Snowpack React Handle Unused Files Demo
=================================

项目中如果某些文件（比如`src/unusedFileHasNode.ts`）未被使用到，只要存在于项目中且没有显式exclude，则`snowpack dev`也会尝试对它进行处理，有时候不太方便。

```
npm install
npm run demo
```

会报错：

```
snowpack

▼ Console

[snowpack] ! building dependencies...
[snowpack] Package "path" not found. Have you installed it? 

error Command failed with exit code 1.
```
