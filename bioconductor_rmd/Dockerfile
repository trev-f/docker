# set base image
FROM bioconductor/bioconductor_docker:RELEASE_3_14

# install packages for rmarkdown
RUN R -e "install.packages(c('base64enc', 'htmltools', 'jquerylib', 'markdown', 'rmarkdown', 'tinytex'), repos = 'https://packagemanager.rstudio.com/all/__linux__/focal/latest')"
