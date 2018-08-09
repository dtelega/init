FROM debian:8.1

MAINTAINER dtelega <dtelega@student.unit.ua>

# Install.
RUN \
  apt-get update && \
  apt-get -y upgrade && \
  apt-get clean
#  apt-get install git -y && \
#  apt-get install openssh-server openssh-client -y
  
# Set environment variables.
ENV HOME /root

# Define working directory.
WORKDIR /root

# Define default command.
CMD ["bash"]

# docker-machine create --driver virtualbox Char
# eval $(docker-machine env Char)


# How to build it?
# docker build -t system .

# How to run it?
# docker run --rm -ti system
