# Puppet Development Kit tool
Docker image for Puppet Development Kit tool

## How to
Execute into your Puppet module path:
```
docker run --rm -ti -v ${PWD}:/app eoldavix/pdk [option]
```

- Example validation puppet code
  ```
  docker run --rm -ti -v ${PWD}:/app eoldavix/pdk validate puppet
  ```
