This chart is deploying the todo-app.

## Adding Helm Repository and Installing Application

### 1. Add Helm Repository

```bash
helm repo add Helm-Application-Repo 'https://raw.githubusercontent.com/meraluguz/Helm-Application-Repo/main'
```

### 2. Install Todo Application

```bash
helm install github-repo-release-todo Helm-Application-Repo/todochart
```


### 3. Install Guestbook Application

```bash
helm install github-repo-release-guest Helm-Application-Repo/Guestbook
