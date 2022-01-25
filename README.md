# multus-service-demo

This repository contains resources used in [multus-service](https://github.com/k8snetworkplumbingwg/multus-service) demo.


### Contents

This repository contains following files:

- multus-service-demo1.yaml: Kubernetes resource manifest file for demo1
- fedora-nginx/Dockerfile: container's Dockerfile used in demo
- fedora-tools/Dockerfile: container's Dockerfile used in demo

In addition, [its github packages](https://github.com/redhat-nfvpe/multus-service-demo/pkgs/container/multus-service-demo) contains container images which is used in the demo (fedora-nginx and fedora-tools).

### Note

#### Why we need container images (not usual nginx container) for demo?

Two container, fedora-nginx and fedora-tools, installs several tools (iproute, wireshark-cli and so on) to check network connectivity in troubleshooting and to check network configuration in container, so it is good to run in the demo, however, it is not required for multus-service, of course, hence you can setup multus-service without above tools.
