FROM nciccbr/ccbr_baser:latest
RUN apt-get update && apt-get install --fix-missing -y libharfbuzz-dev libfribidi-dev libproj-dev
RUN mkdir -p /opt2/ && mkdir -p /data2 && mkdir -p /repo
WORKDIR /repo
COPY . .
RUN Rscript install_packages.R 
