FROM python:3.10-buster

USER root

RUN apt update

RUN useradd -ms /bin/bash vscode

USER vscode

RUN python3 -m pip install --upgrade pip && \
    pip3 install yapf flake8 ipykernel
