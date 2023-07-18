# dubbd-keycloak
A Defense Unicorns Big Bang Repo with Keycloak

## Build Package
```
zarf package build --confirm
```

## Deploy Package
Ensure that the `bigbang.dev.cert` and `bigbang.dev.key` files exist in the deploy directory before 
running the following command:

```
zarf package deploy zarf-package*.tar.zst --confirm
```
