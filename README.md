# Welcome to the FundRequest Toolbox

This git repo contains support tool / utilities scripts to help building, developing and running of the different MVP components


# INSTALL


The toolbox is a combination of Docker images and shell scripts.


```bash
git clone https://gitlab.fundrequest.io/fundrequest/toolbox.git
toolbox/install
```

# INVENTORY


The toolbox currently contains the following modules:

- [x] `testrpc` - Fast Ethereum RPC client for testing and development 
- [ ] `front-end` - FundRequest Front-end module
- [x] `back-end` - FundRequest Front-end module

# USAGE

```bash
usage: toolbox ACTION MODULE

FundRequest Toolbox used to setup several FundRequest modules

ACTION:
   install                Install the module
   remove                 Remove the module
   start                  Start the module
   stop                   Stop the module
   restart                Restart the module
   update                 Update the module

MODULE:
   all                    Target all the supported modules
   testrpc                Fast Ethereum RPC client for testing and development
   front-end              FundRequest Front-end module
   back-end               FundRequest Front-end module
```

