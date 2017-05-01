# vcsim
This is a Dockerfile containing the newest incarnation of vCenter Simulator (vcsim), located in the [VMware VIC repository](https://github.com/vmware/vic/tree/master/cmd/vcsim)

## build
```
docker build -t vcsim .
```

## run
```
docker run -p 8989:8989 vcsim
```


## Wish list

1. It should work with PowerCLI :P
2. Pass env variables on run to specify number of datacenters, hosts, etc
3. Use a JSON or XML file to pass in completely definable simulated infrastructure (Pull data from my prod environment, put it in a sim)
