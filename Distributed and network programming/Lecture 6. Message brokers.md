
# Making  sockets easier to work with
- Observartion
- Alternative: ZeroMQ
# Patterns 
- Request-reply
- Publish-subscriber


```Python
import time
import zmq

context = zmq.Context()
socket = context.socket(zmq.REP)
socket.bind("tcp://*:")
```
