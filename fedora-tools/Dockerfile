FROM docker.io/fedora:35

LABEL org.opencontainers.image.source https://github.com/redhat-nfvpe/multus-service-demo
RUN dnf update -y && \
	dnf install -y iproute iptables-nft iptables iputils net-tools procps-ng ltrace strace tcpdump wireshark-cli bind-utils
