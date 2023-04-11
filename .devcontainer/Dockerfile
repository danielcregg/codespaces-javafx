# Use the latest version of the base image
FROM mcr.microsoft.com/devcontainers/base:jammy

# Install window manager, X server, x11vnc (VNC server), noVNC (VNC client)
ENV DISPLAY=":0"
RUN apt install openbox xvfb x11vnc -y
RUN wget https://github.com/novnc/noVNC/archive/refs/tags/v1.4.0.zip -P/tmp && \
    unzip /tmp/v1.4.0.zip -d /tmp && \
    mv /tmp/noVNC-1.4.0 /opt/noVNC && \
    rm -rf /tmp/noVNC-1.4.0 /tmp/v1.4.0.zip && \
    chown -R ubuntu:ubuntu /opt/noVNC
