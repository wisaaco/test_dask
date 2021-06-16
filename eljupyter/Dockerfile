FROM daskdev/dask-notebook

RUN apt-get update -y && apt-get install -y python3-pip libsnappy-dev
RUN pip install dask
RUN pip install distributed
RUN pip install xarray
