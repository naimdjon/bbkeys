bbkeys
======

A git repo for bbkeys.

Depends on `libbt-dev`. Use `apt-get` or `yum` to install `libbt-dev`. 

Building `bbkeys` from the source:

``` 
make -f Makefile.cvs all
./configure && make && sudo make install
```
I like to keep self compiled stuff on a separate place than those installed with a package manager, so in my machine I did:
`./configure --prefix /opt/bbkeys    &&   make    &&    sudo make install`.

