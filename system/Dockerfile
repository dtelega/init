FROM debian:8.1

MAINTAINER dtelega <dtelega@student.unit.ua>

# Install.
RUN \
  apt-get update && \
  apt-get -y upgrade && \
  apt-get clean
  
# Set environment variables.
ENV HOME /root

# Define working directory.
WORKDIR /root

# Define default command.
CMD ["bash"]
