README
======

Backported patches made to open source components are logged in this repository.

More information can be found in the README files contained in the subdirectories, such as origin, 
changes made by ITRS, build setup (server and compiler) as well as configuration options applied.

Naming convention
-----------------

    <package name>-<package version>-<itrs product name>-<itrs product version>

For example: openssl-1.0.2g-geneos-v3.6.0

Applying patches
----------------

Patches are named in order of application. You can then apply the patches to upstream package distribution

Downloads
---------

Downloads are provided in the "Releases" tab for the Github project.

A summary of downloadable packages per version are provided in the "checksum" directory. These are clear-signed using
the ITRS DevOps PGP key - please import the itrs.asc public key to verify the signed content. 
