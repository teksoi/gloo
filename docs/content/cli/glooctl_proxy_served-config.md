---
title: "glooctl proxy served-config"
weight: 5
---
## glooctl proxy served-config

dump Envoy config being served by the Gloo xDS server

### Synopsis

dump Envoy config being served by the Gloo xDS server

```
glooctl proxy served-config [flags]
```

### Options

```
  -h, --help   help for served-config
```

### Options inherited from parent commands

```
  -c, --config string       set the path to the glooctl config file (default "<home_directory>/.gloo/glooctl-config.yaml")
  -i, --interactive         use interactive mode
      --kubeconfig string   kubeconfig to use, if not standard one
      --name string         the name of the proxy service/deployment to use (default "gateway-proxy")
  -n, --namespace string    namespace for reading or writing resources (default "gloo-system")
      --port string         the name of the service port to connect to (default "http")
```

### SEE ALSO

* [glooctl proxy](../glooctl_proxy)	 - interact with proxy instances managed by Gloo
