# eos2.1-ubuntu-20.04-toolchain
EOSIO eos 2.1.x / eosio.cdt 1.8.1 toolchain image  

# build 
```
cd eos2.1-ubuntu-20.04-toolchain
docker build --rm --tag eos2.1-ubuntu-20.04-toolchain .
```

# run 
```
docker run --rm -v $PWD -ti eos2.1-ubuntu-20.04-toolchain /bin/bash
```

