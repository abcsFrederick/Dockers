FROM nciccbr/ccbr_baser:latest
RUN pwd
RUN ls -larth .
RUN ls -larth /
RUN mkdir -p /opt2/ && mkdir -p /data2 && mkdir -p /repo
WORKDIR /repo
RUN ls -alrth /repo
COPY . .
RUN ls -alrth /repo
RUN tree /repo
WORKDIR /opt2
RUN Rscript /repo/install_packages.R 
