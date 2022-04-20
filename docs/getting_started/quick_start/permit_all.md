# Permit All

## Start PDP Server with Policy File

```
pdpserver -v 3 -p examples/01-intro/all-permit.yaml
```

## Make Request


```
pepcli -i examples/01-intro/all-permit.requests.yaml test
```

