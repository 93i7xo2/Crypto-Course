# ECB Mode / Cut & Paste

* `server.py` : target server
* `solve.py` : solution script
* `flag` : the flag

You can use the following command to start up the server.

```bash
socat TCP-LISTEN:20000,fork EXEC:'python ./server.py'
```

