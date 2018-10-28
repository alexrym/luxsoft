FROM centos

RUN yum install -y git 
RUN mkdir /code
WORKDIR /code
ARG USERNAME
ARG EMAIL
RUN git config --global user.name $USERNAME
RUN git config --global user.email $EMAIL
CMD /usr/bin/git clone https://github.com/alexrym/luxsoft.git && /bin/bash
