# GGN-SDK

a python sdk for ggn
---

USAGE:

```python
# import the library
from lib.ggn_client import GGNClient, GGNClientException

# obtain your token (via env var, args, hardcoding, or some other way)
token = "YOUR GGN API TOKEN"

# create the GGNClient with your token
client = GGNClient(TOKEN)

# use the client to hit the api
api_version_data = client.index()
```
