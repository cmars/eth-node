# k8s-ethnode

Experiments in running sovereign Ethereum nodes.

# Platform

Assuming you have Rancher k3s installed on a server with sufficient specs.

Configs assume a namespace `kubectl create namespace eth-node`.

Some overlays and configs might be homelab site-specific.

# Deploy

    kubectl apply -k ./mainnet

for example.

