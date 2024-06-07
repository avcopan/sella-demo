# sella-demo
Basic demo of a TS optimization with Sella

Steps to run this demo:

1. Install [Pixi](https://pixi.sh/latest/)
```
curl -fsSL https://pixi.sh/install.sh | bash
```

2. Create the environment.
```
pixi install  # in this directory
```

3. Activate the environment.
```
pixi shell  # in this directory
```

4. Pip install sella
```
pip install git+https://github.com/zadorlab/sella.git@master --no-deps
```

5. Open the notebook in Jupyter. (This one just shows basic usage)
```
jupyter notebook demo.ipynb
```

6. The better demo with a relaxed scan uses some functions from the dev branch of my
AutoChem repo, which can be installed as follows:
```
pip install git+https://github.com/avcopan/autochem.git@dev --no-deps
```

7. Open the notebook in Jupyter. (This one just shows basic usage)
```
jupyter notebook demo-with-scan.ipynb
```


