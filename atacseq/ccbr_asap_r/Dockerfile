FROM library/r-base:4.1.1
RUN mkdir -p /opt2/ && mkdir -p /data2
WORKDIR /opt2
COPY install_packages.R .
RUN Rscript install_packages.R .
