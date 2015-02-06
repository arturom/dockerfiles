FROM arturom/ubuntu:latest

RUN \
  apt-get update && \
  apt-get install -y nodejs nodejs-legacy npm && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

CMD ["bash"]
