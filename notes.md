# Github CLI

```
gh auth login
gh repo create gen-ai --public
git init gen-ai
cd gen-ai
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```


# `uv` as dependency manager

```
uv python install 3.11
uv init gen-ai --python=3.11
cd gen-ai
uv venv
# uv add package
uv sync
```

* [Install & Manage Python Versions](https://docs.astral.sh/uv/guides/install-python/)
