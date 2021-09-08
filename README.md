# ard-demo-notebooks

Demo ARD notebooks for running locally in Jupyter or converting to a Docker image

### Cloning and installing dependencies

To run locally, clone this repo:

```bash
$ git clone https://github.com/maxar-analytics/ard-demo-notebooks.git
```

Navigate into your local clone and install dependencies from `requirements.txt`:

```bash
$ pip install -r requirements.txt
```

Then install [`vizard`](https://github.com/maxar-analytics/vizard):

```bash
$ pip install git+ssh://git@github.com/maxar-analytics/vizard --extra-index-url https://packages.ard.maxar.com
```
