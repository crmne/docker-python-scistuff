FROM python:2.7
MAINTAINER Carmine Paolino <carmine@paolino.me>
RUN apt-get update && apt-get -y install \
    gfortran \
    libopenblas-dev
RUN pip install --no-cache-dir \
    numpy \
    scipy \
    matplotlib \
    scikit-learn
