# Local Setup

We need to setup the Themis project on local machine to we can run some examples and understand it well.

## Clone The Project

Run following command to clone project on the local machine.

```
git clone git@github.com:infobloxopen/themis.git
```

## Build Binaries

Once you clone the repo, you need to build the binaries.

1\. Change directory to themis:

```
cd themis
```
2\. Use make command to build the project:
```
make build
```

Please verify that it will generate `build` directory. It will contain following files:

- `egen`
- `mkpiphandler`
- `papcli`
- `pdpserver`
- `pepcli`
- `pipcli`
- `pipjcon`