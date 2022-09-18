FROM docker.io/fedora:36

LABEL org.opencontainers.image.source https://github.com/redhat-nfvpe/multus-service-demo
RUN dnf install -y http://nginx.org/packages/rhel/7/noarch/RPMS/nginx-release-rhel-7-0.el7.ngx.noarch.rpm && \
    dnf install -y nginx iproute iptables iptables-nft iptables-legacy iputils net-tools tcpdump wireshark-cli && \
    systemctl enable nginx

CMD /sbin/init
