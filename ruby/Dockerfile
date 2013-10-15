FROM ubuntu
RUN apt-get -y update
RUN apt-get -y install build-essential zlib1g-dev libssl-dev libreadline6-dev libyaml-dev wget
RUN wget http://cache.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p247.tar.gz -O- | tar -xzf-
RUN cd ruby-2.0.0-p247; ./configure --prefix=/usr/local; make; make install
