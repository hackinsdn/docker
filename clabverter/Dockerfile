FROM alpine:3.23

RUN cd /tmp \
 && wget https://github.com/srl-labs/clabernetes/releases/latest/download/clabernetes_linux_x86_64.tar.gz \
 && tar -xzf clabernetes_linux_x86_64.tar.gz \
 && install -o root -g root -m 0755 clabverter /usr/local/bin/clabverter \
 && rm -rf /tmp/*
