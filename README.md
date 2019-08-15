# GitHub Actions Token Retriever YAML edition (ghatr-yaml)

Retrieves the token for GitHub Actions. **Only to be used for debugging in a private repository**.

# Usage

See [action.yml](action.yml) for more information.

```yaml
steps:
- uses: brxxn/ghatr-yaml@v1
  with:
    repo-token: ${{ secrets.GITHUB_TOKEN }}
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE).
