# docker-yumrepo

Run a yum repo in docker, including repo updates in a docker run-n-exit command 

## Setup

See "runme" for an example - you can even use that script directly.  It sets the host port to run the http server on as well as mounts a host directory (so that you can persist your RPMs) inside the container. 

## Repo updates

See "runme_update" - configured similarly to "runme", this expects that you have put new rpms (or removed some) in the RPMS dir that's mounted into the yumrepo container.  It will generate a new yum data structure reflecting the current contents.


## Possible enhancements

- https

