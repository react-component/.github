<div align="center">
  <h1>React Component GitHub Defaults</h1>
  <p><sub><a href="https://ant.design"><img alt="Ant Design" height="14" src="https://gw.alipayobjects.com/zos/rmsportal/KDpgvguMpGfqaHPjicRK.svg" style="vertical-align: -0.125em;" /></a> Part of the Ant Design ecosystem.</sub></p>
  <p>🧰 Shared GitHub community files and workflow templates for rc-component packages.</p>
</div>

<p align="center">English | [简体中文](./README.zh-CN.md)</p>

Shared GitHub community files and workflow templates for the React Component organization.

## Recommended CI

New rc-component repositories should use the reusable workflow from `react-component/rc-test`:

```yml
jobs:
  test:
    uses: react-component/rc-test/.github/workflows/test-utoo.yml@main
    secrets:
      CODECOV_TOKEN: ${{ secrets.CODECOV_TOKEN }}
```

## Workflow Template

1. Open the target repository on GitHub.
2. Go to the Actions tab.
3. Click New workflow when the repository already has workflows.
4. Choose the React Component workflow template.

See GitHub's documentation for [sharing workflows with an organization](https://docs.github.com/en/actions/using-workflows/sharing-workflows-secrets-and-runners-with-your-organization).
