# hash:sha256:dce5f9d5f1079e8c3df8f891cbca7838ef3f170d11fb9af894d85c1543838d61
FROM registry.codeocean.com/codeocean/miniconda3:4.12.0-python3.9-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        anaconda \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    optuna \
    scikit-learn
