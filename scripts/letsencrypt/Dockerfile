FROM bitnami/minideb

RUN install_packages \
      gcc \
      python-pip && \
    pip install \
      setuptools \
      wheel && \
    pip install \
      certbot \
      certbot-dns-route53 \
certbot-dns-dnsimple
