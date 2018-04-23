Provides a storage finder for graphite-api to read from graphouse.

Example configuration:

```yaml
# Tell graphite-api to use graflux to find metrics
finders:
  - graphouse-graphite-api.graphite.GraphouseFinder

# graphouse specific configuration
graphouse:
  url: http://10.10.0.10:2005
```

License: MIT
