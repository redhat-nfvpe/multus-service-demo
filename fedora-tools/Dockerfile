FROM docker.io/fedora:36

LABEL org.opencontainers.image.source https://github.com/redhat-nfvpe/multus-service-demo
RUN dnf update -y && \
	dnf install -y bind-utils iproute iptables iptables-nft iptables-legacy iputils net-tools ltrace procps-ng strace tcpdump wireshark-cli
