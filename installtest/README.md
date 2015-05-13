# install test

`install_request.rspec` contains an unbound RSpec that can be used with either InstaGENI or ExoGENI.

`install.sh` contains a simple install script which touches the file `/local/myspecialfile`

`install.sh.tar.gz` is a tarball containing the single file `install.sh`

## Quickstart

 1. From the *Add Resources* Jacks page load the following url:
```
https://raw.githubusercontent.com/seledwards/helloworld/master/installtest/install_request.rspec
```
 2. Bind the node to an InstaGENI or ExoGENI aggregate.
 3. Reserve the topology.
 4. When the node is ready, login and check for the existance of the empty file `/local/myspecialfile`
