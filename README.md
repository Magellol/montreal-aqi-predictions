# api-predictions

Predicting AQI values in Montreal, QC. Read the accompanying [blog post](https://tlbvr.com/blog/predicting-montreal-aqi) for more details.

```console
jupyter notebook
```

Note: if dependencies change in `requirements.txt`, you must nuke the previous `.venv.`

```console
rm -rf .venv

# Assuming usage of direnv
direnv reload
```

You can also open this notebook in google colab if you need a GPU.

https://colab.research.google.com/github/Magellol/aqi-predictions/blob/main/index.ipynb

## Disclaimer

This project uses nix to setup the python environment. Nix flake configuration inspired by https://www.reddit.com/r/NixOS/comments/q71v0e/comment/hgn4sar/
