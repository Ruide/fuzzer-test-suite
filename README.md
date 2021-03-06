# fuzzer-test-suite

This is a set of tests (benchmarks) for fuzzing engines (fuzzers).

The goal of this project is to have a set of fuzzing benchmarks derived from real-life
libraries that have interesting bugs, hard-to-find code paths, or other
challenges for bug finding tools.

In addition, this project provides a fuzzing engine
[comparison framework](engine-comparison/) to execute A/B tests between
different fuzzing configurations.

The current version supports [libFuzzer](http://libFuzzer.info) and
[AFL](http://lcamtuf.coredump.cx/afl/).  In future versions we may support
other fuzzing engines.

# See also

* [AddressSanitizer](http://clang.llvm.org/docs/AddressSanitizer.html)

# Contributing
See [CONTRIBUTING](CONTRIBUTING) first. 
If you want to add one more benchmark to the test suite,
simply mimic one of the existing benchmarks and send the pull request. 

# Disclaimer
This is not an official Google product.
