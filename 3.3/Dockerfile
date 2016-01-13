FROM python:3.3
MAINTAINER Carmine Paolino <carmine@paolino.me>
RUN apt-get update && apt-get -y install \
    gfortran \
    libopenblas-dev
RUN pip install --no-cache-dir \
    numpy \
    scipy \
    matplotlib \
    scikit-learn
