
To run these tests you must have the loader [./Setup.md](https://github.com/pinf/loader-js/blob/master/docs/Setup.md).

Platform: NodeJS
================

Server-based programs:

    commonjs -v ./tests/demos


Platform: Jetpack
=================

Firefox extensions:

    # Jetpack (assuming SDK activated & FF 4 installed)
    cfx --pkgdir=./demos/JetpackExtension/extension test
