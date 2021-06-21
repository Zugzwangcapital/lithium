What is Lithium?
----------------

Lithium is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Lithium uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Lithium is the name of open source
software which enables the use of this currency.

For more information read the original Lithium whitepaper.


Development Process
-------------------

The `master` branch is regularly built (see `doc/build-*.md` for instructions) and tested, but it is not guaranteed to be
completely stable


Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).
