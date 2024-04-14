```console
jupyter notebook
```

Note: if dependencies change in `requirements.txt`, you must nuke the previous `.venv.`

```console
rm -rf .venv

# Assuming usage of direnv
direnv reload
```

You can also open this notebook in google colab if you need GPUs. You'll have to authorize google to access your github account.

https://colab.research.google.com/github/{org}/{repo}/blob/main/{file}.ipynb

### Disclaimer

Nix flake configuration inspired by https://www.reddit.com/r/NixOS/comments/q71v0e/comment/hgn4sar/