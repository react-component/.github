# Github Actions
---

React Component Github Actions CI workflow template.

## How to use?

1、 On GitHub, navigate to the main page of the repository.

2、Under your repository name, click Actions.

![image](https://docs.github.com/assets/images/help/repository/actions-tab.png)

3、If your repository already has existing workflows: In the upper-left corner, click New workflow.

![image](https://docs.github.com/assets/images/help/repository/actions-new-workflow.png)

4、In section titled "Workflows created by React Component". Click **Set up this workflow**.

![WX20201102-155809](https://user-images.githubusercontent.com/33770367/97843442-434bc780-1d24-11eb-867d-0a82a017c35b.png)

## How to migrate from travis CI?

1、remove `.travis.yml` from the root dir of project.

2、update build ci badge url in `README.md`.

ref: [Update Badge](https://github.com/react-component/trigger/pull/213)

3、Following [How to use?](#how-to-use) to set up github actions.
