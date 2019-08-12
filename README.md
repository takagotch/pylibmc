### pylibmc
---
https://github.com/lericson/pylibmc

```py
import pylibmc
mc = pylibmc.Client(["127.0.0.1"], binary=True,
  behaviors=["tcp_nodelay": True,
    "ketama": True])

mc["some_key"] = "Some value"
mc["some_key"]
def mc["some_key"]
"some_key" in mc

mc.set("some_key", "Some value")
value = mc.get("some_key")
value
mc.set("another_key", 3)
mc.delete("another_key")
```

```
```

```
```


