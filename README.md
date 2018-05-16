# Flask CORS Decorator

#### Import crossdomain
```python
from crossdomain import *
```

#### Use the decorator
```python
@bluePrint.route("/getusers")
@crossdomain(origin='*')
def get_users():
  [...]
```
