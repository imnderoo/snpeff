# Base Image
FROM biocontainers/biocontainers:latest

# Metadata
LABEL base.image="biocontainers:latest"
LABEL version="4.3.1t"
LABEL software="snpeff"
LABEL software.version="4.3.1t"
LABEL description="snpeff"
LABEL license="http://snpeff.sourceforge.net/"
LABEL tags="Genomics"

RUN conda install -c bioconda snpeff=4.3.1t

USER root

WORKDIR /data/

ENTRYPOINT ["snpEff"]

