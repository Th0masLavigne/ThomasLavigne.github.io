# Resume

Create the files `_config.yml` and `_toc.yml`. Then in the cmd realise:


```bash
python3 -m venv ~/venv-quarto
```

```bash
source ~/venv-quarto/bin/activate
```


```bash
pip install jupyter-book ghp-import quarto
```

```bash
# jupyter-book build .
```

```bash
quarto create project
quarto install extension quarto-ext/fontawesome
quarto install extension schochastics/academicons
quarto add mcanouil/quarto-iconify
```
```bash
quarto preview
```

```bash
# si final
quarto render
```


In case of need, before rebuild: `jupyter-book clean .`

Then push to your github pages
```bash
ghp-import -n -p -f _build/html
```

Finally deactivate the environment:
```bash
deactivate
```


Add the `index.html` file to ensure starting in the good readme.