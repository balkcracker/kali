kali 
================================

http://www.kali.org (PENDING)

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers

What is kali?
----------------

kali uses scrypt as a proof-of-work algorithm.
 - 2 minute block targets
 - subsidy halves in 10k blocks (~3.5 days)
 - ~44 million total coins

 - coins per block based on total bitcoins mined/live world population*kali mined+FTSE100
 - 2.5 days approx to retarget difficulty


License
-------
kali is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.




### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./kali-qt_test

