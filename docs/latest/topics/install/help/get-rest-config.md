# edgectl install: Can't retrieve client configuration
 
## The Problem

Ambassador's `edgectl install` uses `kubectl` to communicate with Kubernetes.  

Ambassador was unable to retrieve a client configuration, which  holds the common attributes
that are passed to a Kubernetes client on initialization.

## How to Resolve It

...
