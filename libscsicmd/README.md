libscsicmd
==========

A library to create SCSI commands (CDBs) and parse the results, also for ATA commands and results.

This library doesn't deal with actually submitting the CDBs or getting the results from the storage device, only with
the commands themselves. The actual sending of the command is different between the different OSes and this library
tries to be OS agnostic.

Build
=====

The build system is using [redo](https://github.com/apenwarr/redo), a minimal
`do` script is provided so that the full redo need not be installed.

To build, run:
  ./do

Author
======
Baruch Even <baruch@ev-en.org>
