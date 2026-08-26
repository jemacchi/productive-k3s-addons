# Product

This repository is the curated package layer for extending a Productive K3S cluster.

Use it when you want ready-to-use cluster capabilities rather than assembling every extension by hand.

Examples include management, storage, ingress, registry, and certificate-related packages.

`productive-k3s-core` remains the layer that installs and validates those packages, while `productive-k3s-addons` owns the curated public catalog of add-ons and stacks.

The contract boundary matters:

- this repository names and validates catalog entries such as `nginx` or `base`
- public `core` add-on installation consumes packaged artifacts rather than resolving add-on source names directly
