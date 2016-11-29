FROM andrewosh/binder-base
MAINTAINER Jeff Terstriep <jefft@illinois.edu>

USER root
RUN apt-get install -y libgeos-dev 

USER main
RUN pip install shapely

RUN /home/main/anaconda/envs/python3/bin/pip install shapely
