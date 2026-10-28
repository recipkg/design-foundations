# Design Foundations · Recipkg

**界面设计的基础合同：交互、响应式与无障碍。**

[标准库](https://github.com/recipkg/standard-library) · [配方清单](RECIPE.md) · [构建要求](BUILD_PROMPT.md) · [验收条件](ACCEPTANCE.md) · [参考来源](SOURCES.md)

![从软件与依赖整理配方，再交给 Agent 重建](https://raw.githubusercontent.com/recipkg/recipkg/main/assets/recipkg-cover.png)

这份配方帮助其他软件定义界面质量要求，包括任务流程、状态反馈、键盘操作、响应式布局和可访问性。它是一套可复用的设计合同，不提供运行时 UI 库，也不是厂商设计系统的副本。

## 使用

在产品配方中声明本仓库的完整 Git 提交作为依赖，在自己的构建说明中写清适用范围和验收方式。然后打包产品配方，让 Agent 同时获得递归依赖。具体平台和产品界面仍须实际验证；打包通过不等于完成设计或无障碍认证。

```sh
recipe_dir="$(mktemp -d)"
recipkg pack . -o "$recipe_dir/design-foundations.recipe.tar.gz"
recipkg check "$recipe_dir/design-foundations.recipe.tar.gz"
recipkg build "$recipe_dir/design-foundations.recipe.tar.gz" --lang zh-CN --output "$recipe_dir/build.md"
printf '提示词：%s\n' "$recipe_dir/build.md"
```
