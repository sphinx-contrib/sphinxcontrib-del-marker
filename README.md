# sphinxcontrib-del-marker

The `del-marker` extension allows you to use texts as defined by the HTML5 standard. 

It's a wrapper around the `<del>` tag. 

## Usage

### Install
You can install with pip:

```bash
pip install sphinxcontrib-del-marker
```

### Configure
and add it to `sphinx conf.py`:

```python
# conf.py
...
extensions = ["sphinxcontrib_del_marker"]
...
```

### Use

with directive:
```rst
.. del:: lorem lorem lorem
```


## Roadmap

- [ ] using with sphinx `role`
