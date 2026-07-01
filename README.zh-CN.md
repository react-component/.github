<div align="center">
  <h1>React Component GitHub Defaults</h1>
  <p><sub><a href="https://ant.design"><img alt="Ant Design" height="14" src="https://gw.alipayobjects.com/zos/rmsportal/KDpgvguMpGfqaHPjicRK.svg" style="vertical-align: -0.125em;" /></a> Ant Design 生态的一部分。</sub></p>
  <p>🧰 rc-component 仓库共享的 GitHub 社区文件与工作流模板。</p>
</div>

<p align="center"><a href="./README.md">English</a> | 简体中文</p>

React Component 组织共享的 GitHub Actions 工作流模板。

## 使用方式

1. 进入目标仓库的 Actions 页面。
2. 如果仓库已有工作流，点击 New workflow。
3. 选择 React Component 提供的模板并按需提交。

当前推荐新仓库直接使用 [rc-test](https://github.com/react-component/rc-test) 中的 reusable workflow：

```yml
jobs:
  test:
    uses: react-component/rc-test/.github/workflows/test-utoo.yml@main
    secrets:
      CODECOV_TOKEN: ${{ secrets.CODECOV_TOKEN }}
```
