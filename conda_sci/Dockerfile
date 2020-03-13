FROM conda_base:v0.1

# COPY .condarc /root/



RUN conda clean -i && \
    conda install --yes \
    # cudatoolkit \
    pytorch \
    torchvision \ 
    tensorflow-gpu \
    keras \
    numpy \
    pandas \
    scikit-learn \
    matplotlib \
    seaborn \
    statsmodels  \
    h5py \
    cython \
    dask \
    hdf5 \
    numba \
    scipy \
    sympy \
    xlrd \
    pyarrow \
    cupy && \
    conda clean -afy && \
    find /opt/conda/ -follow -type f -name '*.a' -delete && \
    find /opt/conda/ -follow -type f -name '*.pyc' -delete

# RUN pip install xgboost catboost lightgbm ipdb tqdm hyperopt tpot -i https://mirrors.aliyun.com/pypi/simple/

