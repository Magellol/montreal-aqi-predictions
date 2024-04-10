```console
jupyter notebook
```

Note: if dependencies change in `requirements.txt`, you must nuke the previous `.venv.`

```console
rm -rf .venv
direnv reload
```

### Disclaimer

Nix flake configuration inspired by https://www.reddit.com/r/NixOS/comments/q71v0e/comment/hgn4sar/