FROM daskdev/dask
MAINTAINER nako.sung@navercorp.com

RUN conda install hdfs3 matplotlib -c conda-forge -y
RUN apt-get update -y
RUN apt-get install fonts-nanum-* -y
RUN cp /usr/share/fonts/truetype/nanum/Nanum* /opt/conda/envs/dask/lib/python3.6/site-packages/matplotlib/mpl-data/fonts/ttf/
