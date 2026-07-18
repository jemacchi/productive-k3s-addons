# Relationship with Core and Addons Pro

`productive-k3s-core` is the installation engine for the curated cluster extensions defined here. It discovers add-on metadata, resolves stack membership, and executes normalized hooks.

`productive-k3s-addons` contains:

- `addons/`: curated cluster capabilities that can be installed individually
- `stacks/`: curated grouped extension paths built from those add-ons

`productive-k3s-addons-pro` follows the same repository contract for private content.
