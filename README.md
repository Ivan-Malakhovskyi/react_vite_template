# React + Vite Template

1. Setup:

- after cloning in repo Settings => Pages => Build and deployment => Github
  Actions

![Setup Actions](./src/assets/github-pages_actions.png)

- In Settings repo Workflow permissions => set Read and write permissions and
  Allow GitHub Actions to create and approve pull requests

![Settings GitHub Actions permissions step 1](./src/assets/gh-actions%20setup.png)

2. React router

## If you are using react-router (Якщо ви використовуєте react-router)

```jsx
  <BrowserRouter basename="/repo_name">
    <App />
  </BrowserRouter>,
```
