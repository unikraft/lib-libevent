# lib-libevent
 Unikraft port of libevent, an event notification library

## Build
Libevent depends on the following libraries, that need to be added to
`Makefile` in this order:

* `pthreads`, e.g. `pthread-embedded`
* network stack, e.g. `lwip`
* `libc`, e.g. `newlib`

## Further information
Please refer to the `README.md` as well as the documentation in the
`doc/` subdirectory of the main unikraft repository.
