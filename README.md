# GCR

## Build instructions

You'll need libboost, libdb++, and libminiupnpc.  To install on ubuntu:

```
apt get install libboost-all-dev libdb++-dev libminiupnpc-dev
```

In `src`, execute `make -f makefile.unix` and a `gcrd` executable should be produced.
