FROM ekidd/rust-musl-builder
RUN \
curl -LO https://github.com/facebook/rocksdb/archive/v5.1.2.tar.gz && \
tar xvf v5.1.2.tar.gz && cd rocksdb-5.1.2 && \
sudo make install-static INSTALL_PATH=/usr/local/musl
COPY cargo-config /.cargo/config
