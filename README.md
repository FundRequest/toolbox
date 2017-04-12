# Welcome to the FundRequest Toolbox

This git repo contains support tool / utilities scripts to help building, developing and running of the different MVP components


# INSTALL


The toolbox is a combination of Docker images and shell scripts.


```bash
git clone http://gitlab.fundrequest.io/fundrequest/toolbox.git
cd toolbox
echo "export PATH=$PATH:$PWD/bin" >> ~/.bash_profile
source ~/.bash_profile
```

# INVENTORY


The toolbox currently contains the following functionalities:

* `mvp_testrpc` - Fast Ethereum RPC client for testing and development 
* `Geth Client`
* `MVP Frontend`
* `MVP Backend Core`
* `MVP Backend DB`
* `RabiitMQ`
