badsed on Ethminer-0.9.41-genoil-1.1.7

For GTX970 : 
cmake -DBUNDLE=cudaminer -DCOMPUTE=52 .. 

I have nowhere else to keep this .. 
IF you get protocol errors and a seg fault STOP THE WINDOW MANAGER ( on wily delete LIGHTDM in init.d ) 
don't install : 
 ocl-icd-libopencl1 opencl-headers ( REMOVE THEM ifthey are installed )  
 any of the qtweb stuff - this doesn't have a gui so no need for qt
 libgmp-dev no need to manipulate gmp files
 

WILY DEPS
apt-get install libjsoncpp-dev libjsonrpccpp-tools  libjsonrpccpp-dev libjsonrpccpp-stub0 build-essential git cmake libboost-all-dev  libleveldb-dev libminiupnpc-dev libreadline-dev libncurses5-dev libcurl4-openssl-dev libcrypto++-dev libmicrohttpd-dev libargtable2-dev libedit-dev libv8-dev zlib1g-dev

Install the AMD SDK into /opt it will pick it up 
