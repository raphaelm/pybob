pybob
=====

Python 3 interface for boblightd (LED controller)

Documentation
-------------
It's as simple as typing 
```python
import time
import pybob
b = pybob.Boblights('127.0.0.1')
b.open()
b.set_light(b.get_lights()[0], "FF0000")
time.sleep(10)
b.close();
```

but you if you are interested, check out the module with executing `pydoc pybob`.
