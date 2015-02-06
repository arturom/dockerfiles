FROM arturom/gulp:latest

RUN \
  apt-get update && \
  apt-get install -y php5 && \
  apt-get clean && \
  rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN \
  npm install --silent -g phplint

CMD ["bash"]
