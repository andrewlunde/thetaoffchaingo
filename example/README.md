# Discover CloudFoundry Go Versions

```
ver=$(cf buildpacks | grep go | cut -d '-' -f 4 | cut -d '.' -f 1-3) ; echo ; echo "Browse to this page for golang versions available in this buildpack." ; echo ; echo "https://github.com/cloudfoundry/go-buildpack/releases/tag/$ver" ; echo
```
### Current Go Versions
https://github.com/cloudfoundry/go-buildpack/releases/tag/v1.9.33

Name | Version
------------ | -------------
go | 1.15.12
go | 1.15.13
go | 1.16.4
go | 1.16.5


# Config

Set the PORT Environment variable to override the default (8080)

```
export PORT=8081
```

# Run

Run with Go
```
go run main.go
```
