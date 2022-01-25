FROM docker.io/fedora:35

LABEL org.opencontainers.image.source https://github.com/redhat-nfvpe/multus-service-demo
RUN dnf install -y http://nginx.org/packages/rhel/7/noarch/RPMS/nginx-release-rhel-7-0.el7.ngx.noarch.rpm && \
    dnf install -y nginx iptables net-tools iputils iproute wireshark-cli && \
    systemctl enable nginx

CMD /sbin/init
