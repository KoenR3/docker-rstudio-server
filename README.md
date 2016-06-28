# docker-rstudio-server

This image is meant for workshops using RStudio.  It uses the community edition so there is no load-balancing.

This is the standalone version for testing the Rstudio build, only the datafriend1 user will have data

        docker run -d -p8787:8787 --name rstudio -v <hostdir>:/home/datafriend1 koenr/docker-rstudio-server
