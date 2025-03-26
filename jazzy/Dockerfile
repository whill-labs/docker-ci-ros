FROM osrf/ros:jazzy-desktop-full

RUN apt-get update && \
    apt-get install -y \
        ccache && \
    apt-get autoclean && \
    apt-get autoremove && \
    rm -rf /var/lib/apt/lists/*

