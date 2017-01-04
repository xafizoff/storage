Storage engine, LSM-style
=========================


General information
--------------------

This repository contains storage engine that implements persistent key-value storage
in log-structured merge tree (LSM) style. Persistence here means that data once fixed
in transaction commit will not change in future.


Copyright information
---------------------

Copyright (C) 2017 Serguey Zefirov


Documentation
-------------

A preliminary version can be found [here](https://docs.google.com/document/d/1EYS100swps1V9PVnnVdY2qHkF1u4zRooqH4w76jbsEk/pub).


Source files
-----

S.hs - storage engine,
TS.hs - tests.

