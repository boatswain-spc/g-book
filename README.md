# Example from Kubernetes

This example shows how to build a simple, multi-tier web application using Kubernetes and Docker.

The example consists of:
- A web frontend
- A redis master (for storage and a replicated set of redis slaves)

The web front end interacts with the redis master via javascript redis API calls.


