FROM ghcr.io/osgeo/gdal:ubuntu-full-3.8.4
RUN \
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs >> rustup.sh && \
    chmod +x ./rustup.sh && \
    ./rustup.sh -y && \
    apt update && \
    apt install -y build-essential libssl-dev