# Visdom-Helper

This is a simple helper class that makes the awesome `visdom` library easier to use.

### Todo
- [ ] add `pip` build chain

## Download
[ ] todo item

## Usage

First try to setup a dashboard.
```python
from visdom-helper import Dashboard

vis = Dashboard('title-of-this-dashboard')
# Now you can  add plots to it.


```

Existing plots are automatically updated.
```python
vis.plot('title-of-plot/name-of-plot', 'type-of-plog', *arg, **args)
```

```python
vis.plot('title-of-plot/name-of-plot', 'type-of-plog', *arg, **args)
```
