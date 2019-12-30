# GitHub Actions Bash

[**WEB**](https://tomashubelbauer.github.io/github-actions-bash)

Using `ubuntu-latest` this does not work:

```sh
if [ -f *.eml ]; then
  echo "Have files"
else
  echo "Don't have files"
fi
```

But this works on WSL.

## To-Do

### Check out Bash version and other discrepancies to find the source of the difference
