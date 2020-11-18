# Experimental controller that scans container registries

https://github.com/fluxcd/image-reflector-controller

## Kubernetes Controller

How does it work?

## Where to start?

https://github.com/fluxcd/image-reflector-controller/blob/b2e4bfed35a47271710e553d5f649fe973ece70a/main.go

Find the implementations of this interface: https://godoc.org/sigs.k8s.io/controller-runtime/pkg/reconcile#Reconciler

There are two [Controllers](https://kubernetes.io/docs/concepts/architecture/controller/). 

https://github.com/fluxcd/image-reflector-controller/blob/b2e4bfed35a47271710e553d5f649fe973ece70a/main.go#L97-L117

## Threads to pull on

How do the two controllers interact?

Would this code benefit from a persistent database?
