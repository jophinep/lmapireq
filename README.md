lmapireq
========

Used to make CollabNet Lab Management REST API Requests simpler (unofficial)

```shel
--------------------------------------------------------------------------------------------------------
Name: lmapireq
Full Name: Lab Management API Requester
--------------------------------------------------------------------------------------------------------
Description
--------------------------------------------------------------------------------------------------------
Used to make Lab Management API Requests simpler

Dependencies:
* BASH
* Python
* /usr/bin/getAuthTokenLM script (https://mgr.cloud.maa.collab.net/developer/rest_api_authentication.html#signing)

Parameters:
-h | --host     host-url
-a | --apikey   apikey of the user
-u | --user     username
-i | --uri      api access uri
-m | --method   REST API methods like POST/PUT/DELETE (not needed if request is GET, GET is default)
-p | --param    JSON parameters required if method is specified (-m or --method option)

Usage:

lmapireq -h https://mgr.cloud.maa.collab.net -a acdba630-84e8-13a1-816d-3f4cb51af8eb -u myuser -i hosts/cu008.cloud.maa.collab.net

(or)

lmapireq --host https://mgr.cloud.maa.collab.net -a acdba630-84e8-13a1-816d-3f4cb51af8eb -u myuser --uri hosts/cu010.cloud.maa.collab.net --method POST --param '{"name":"snapshot-name5", "desc":"Snapshot description"}'
--------------------------------------------------------------------------------------------------------
```
