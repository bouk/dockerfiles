FROM ubuntu
RUN apt-get install -y wget
RUN wget -O - http://nodejs.org/dist/v0.10.20/node-v0.10.20-linux-x64.tar.gz | tar xzf - -C /usr/local/
RUN mv /usr/local/node-v0.10.20-linux-x64 /usr/local/node
RUN ln -s /usr/local/node/bin/node /usr/local/bin/node
RUN ln -s /usr/local/node/bin/npm /usr/local/bin/npm
