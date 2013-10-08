BASE ubuntu
RUN add-apt-repository -y ppa:ubuntu-toolchain-r/test
RUN apt-get update
RUN apt-get install -y gcc-4.8 g++-4.8
RUN update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 20
RUN update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-4.8 20
RUN update-alternatives --config gcc
RUN update-alternatives --config g++
