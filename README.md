# Linux 与 Shell 基础 · OpenSkill Galaxy

面向编程学习者计算机专业学生后端开发运维开发数据分析和准备使用Ubuntu环境的人系统学习Linux文件系统常用命令权限进程软件包Shell脚本日志网络命令环境变量和开发环境配置的静态学习模块。

[开始学习](https://openskill-galaxy.github.io/module-linux-shell/) · [学习路线](https://openskill-galaxy.github.io/module-linux-shell/?page=%2Froutes) · [题库练习](https://openskill-galaxy.github.io/module-linux-shell/?page=%2Fquestions) · [案例训练](https://openskill-galaxy.github.io/module-linux-shell/?page=%2Fcases) · [返回主站](https://openskill-galaxy.github.io/)

本模块当前公开 **4 门课、8 节讲义、26 道练习题、3 套试卷和 1 个案例**。打开课程页可进入本章练习。题库记录最近作答结果，并在到期时给出复习入口。案例可保留草稿、导出作品和收回他人评语。

## 本地开发

使用 Node.js 22。课程、讲义和题库位于 [public/data](public/data/)，编辑后先校验再构建。

```bash
npm ci
npm run dev
node scripts/validate-data.mjs
npm run build
npm run preview
```

`main` 分支更新后由 GitHub Actions 发布到 GitHub Pages。[模块维护说明](https://github.com/openskill-galaxy/openskill-galaxy-tools/blob/main/MODULE_WORKFLOW.md) · [发布核验](https://github.com/openskill-galaxy/openskill-galaxy-tools/blob/main/GITHUB_PAGES_DEPLOY_GUIDE.md)

[MIT 许可](https://opensource.org/license/mit)
