# ENTRYPOINT

> CMD \["executable", "param1", "param2"]

> CMD command param1 param2

entrypoint specifies the default executable to be run. When the container starts.



## ENTRYPOINT ≠ CMD

entrypoints are instructions in docker for defining the default command to run when a container starts

### The key difference

CMD is more flexible and can be overridden when running the container

While ENTRYPOINT defines the main command that cannot be easily overriden&#x20;

Think of CMD as providing default executable. Which can be changed.

ENTRYPOINT as setting a fixed starting point for your container,

If both are used CMD arguments will be passed to entrypoint.
