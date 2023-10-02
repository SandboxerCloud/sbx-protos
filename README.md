# Sandboxer Protobuf definition
This repo contains the proto definitions used across all the repositories

## Services

### Sandboxer Front Controller
In charge of interacting with the client

### Sandboxer Back Controller
In charge of interacting with the worker

### Sandboxer Worker Controller
In charge of interacting with the controller


```
+----------------+    front    +-----------------+    Back     +-----------------+
|                |   ------>   |                 |  <-------   |                 |
|     Client     |             |    Controller   |    Worker   |     Worker      |
|                |             |                 |   ------>   |                 |
+----------------+             +-----------------+             +-----------------+
```


