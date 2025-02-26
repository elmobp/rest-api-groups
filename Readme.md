Forked:

Very basic sample:

Edit  TrustFrameworkExtensions.xml and adjust ServiceUrl to a external webhook that returns the following
```json
["group1","group2","group3"]
```


Then test this aginst an IDP and see what comes back under groups
