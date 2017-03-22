SocketLabs Python
=======================

SocketLabs-Python is a Python interface to the [SocketLabs](https://www.socketlabs.com)
API

## Installation:

```
pip install socketlabs
```

## Quickstart:

```
python
>>> from socketlabs import SocketLabs
>>> username = <username>
>>> password = <password>
>>> serverid = <serverid>
>>> socketlabs = SocketLabs(username=username, password=password,
                            serverid=serverid)
>>> failed = socketlabs.failedMessages()
```
