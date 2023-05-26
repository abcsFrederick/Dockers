FROM nciccbr/ccbr_baser:latest
RUN mkdir -p /opt2/ && mkdir -p /data2 && mkdir -p /repo
WORKDIR /repo
COPY . .
WORKDIR /opt2
RUN Rscript /repo/install_packages.R 
