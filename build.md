# Linux Source Build  
run `apt install build-essential cmake cmake-data qt5-default -y`, make sure gcc version  
run `wget https://dl.bintray.com/boostorg/release/1.66.0/source/boost_1_66_0.tar.gz && tar zxvf boost_1_66_0.tar.gz && rm boost_1_66_0.tar.gz -f && cd boost_1_66_0` to get boost-lib-source  
run `./bootstrap.sh && ./b2 && ./b2 install && cd ../ && rm boost_1_66_0 -rf` to build and install boost  
run `git clone https://gitee.com/yxom-fylzz/varcoin && cd varcoin`  
run `cmake . && make`  
run `cd ../ && git clone https://gitee.com/yxom-fylzz/varcoin-wallet-gui && cd varcoin-wallet-gui && cp ../varcoin/* varnote -r`  
run `cmake . && make`  
  
enjoy。。。
