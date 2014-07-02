chan-test
=========

Asterisk channel driver for testing purposes.

Installing
==========

    apt-get install build-essential asterisk-dev
    make
    make install

Usage
=====

To create a new test channel:

    asterisk -r
    test new <exten> <context> [cid_num] [cid_name]