# Permit All

## Prerequisites

1. You need to do [Local Setup](../local_setup.md).
2. Change directory to build. `cd build
`
## Start PDP Server

You need to run the following to start PDP service. 

```
./pdpserver -v 3 -p ../examples/01-intro/all-permit.yaml
```

You can in above command that we have passed policy file by using -p 

## Make Request


```
pepcli -i examples/01-intro/all-permit.requests.yaml test
```

