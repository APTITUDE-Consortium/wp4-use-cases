FROM ubuntu:24.04

RUN apt update
RUN apt install -y pandoc python3 python3-venv python3-natsort texlive-luatex unzip wget
RUN wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.9.37/quarto-1.9.37-linux-amd64.deb
RUN dpkg -i quarto-1.9.37-linux-amd64.deb
RUN quarto install chrome-headless-shell

WORKDIR /D4.1
