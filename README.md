# TheGitOps

Used commands


```bash
export export GITHUB_TOKEN=<my-token>
  # Run bootstrap for a public repository on a personal account
flux bootstrap github --owner=josmare --repository=TheGitOps --private=false --personal=true --path=clusters/my-cluster

```