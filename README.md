# not-open-source

在 Github 上 不开源/不完全开源 的具有一定知名度的项目(markdown 型不计入，需要项目主体构成是代码)

## 声明

1. 不开源是作者的权力，除所有者外任何组织或个人不得强制其开源。（因此本仓库不叫 fake-open-source，某些项目因为情况特殊不宜开源可以理解）
2. 在 Github 上存放项目不等于项目开源。
3. 公开源代码但不开放源码许可也不等于项目开源。
4. 源码开源，文档收费将另行列出。

## 补充说明
1. 开源，但代码编译出的程序与 release 版本程序不一致（指外观、功能上的不一致，参考 [Reproducible_builds](https://en.wikipedia.org/wiki/Reproducible_builds)）也视为不完全开源（[VS Code](https://github.com/microsoft/vscode.git) ，编译出来的是 VSCodium ，官方叫做 Code-OSS ，但因未完成源码审查构建暂时先不分类）
2. 开源，但携带不影响其功能实现的二进制程序视为完全开源（如 [Calci-kernel](https://github.com/Iraka-C/Calci-kernel)，仓库名称与描述显式声明了是 Calci 的组件，不易混淆，因此携带 Calci 的二进制程序不视为不完全开源）
3. 开源，但其为闭源程序的开源实现或部分视为完全开源，但名称应有区分，且开源部分能独立工作。（如 Chromium，名称与 Chrome 有明显区分，Chrome 不开源但 Chromium 仍视为完全开源）
4. 开源，如果有引入的外部功能或 SDK 依赖闭源的第三方服务需要显式声明，如文件转换服务依赖在线的网站 API 实现，但部分不属于代码实现范畴的数据类服务不计算在其中，如某网站的第三方客户端依赖原网站 API，天气程序程序调用第三方天气 API。

## 正文

| 名称 | 类型 |
| - | - |
| [sablejs](https://github.com/sablejs/sablejs) | 核心代码不开源 |
| [edusoho](https://github.com/edusoho/edusoho) | 前端代码不开源 |
