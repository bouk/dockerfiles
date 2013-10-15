FROM ubuntu
RUN apt-get install -y build-essential libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev wget
RUN wget http://python.org/ftp/python/2.7.5/Python-2.7.5.tgz -O- | tar -xzf-
RUN cd Python-2.7.5; ./configure; make; make install
