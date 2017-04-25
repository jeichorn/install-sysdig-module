# install-sysdig-module

To install the module run

```
docker run --rm -ti --privileged etown/install-sysdig-module
```

After that you can use
``
docker run -i -t — name sysdig — privileged -v /var/run/docker.sock:/host/var/run/docker.sock -v /dev:/host/dev -v /proc:/host/proc:ro -v /boot:/host/boot:ro -v /lib/modules:/host/lib/modules:ro -v /usr:/host/usr:ro sysdig/sysdig
``
