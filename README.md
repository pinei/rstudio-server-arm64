# rstudio-server-arm64
Compiles RStudio Server (Workbanch) 1.4 and R 4.1.1 for the ARM64 platform / tested on a Raspberry Pi 4 with 4GB ram

To compile from source clone this repository then run

    docker build -tag rstudio-server . && docker run -d -p 8787:8787 rstudio-server

There will be also a precompiled ARM64 version available on hub.docker.com
  
    docker run -d -p8787:8787 pinei/rstudio-server:1.4

user / pass: rstudio
