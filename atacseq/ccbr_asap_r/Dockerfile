FROM nciccbr/ccbr_baser:latest
RUN pwd
RUN mkdir -p /opt2/ && mkdir -p /data2 && mkdir -p /repo
WORKDIR /repo
RUN ls -alrth /repo
COPY . .
RUN ls -alrth /repo
RUN pwd
RUN Rscript install_packages.R 
