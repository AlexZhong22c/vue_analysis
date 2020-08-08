# 手撕 Vue 2.x源码








## 写给自己看

- 所有注释使用 `@note:` 来标注，方便搜索和迁移到v3
- 已修改文件：【方便追溯迁移】
  - `@note:` 增加注释
  - 原项目的 README.md 转移到 README_original.md
- 使用 `git remote` 在两项目间一拉一推
  - `git remote -v`
  - `git remote add upstream`：本质上还是 git remote 操作
  - `git remote set-url origin`：篡改 origin 标识所对应的项目地址
  - (v2.6.11  --> vue2_analysis)