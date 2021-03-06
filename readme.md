LIBCDS 2 - A Compressed Data Structure Library
================================================

Rationale
---------
LIBCDS 2 is the re-coding of [LIBCDS][libcds1] with these goals:

 - 64-Bit support to allow for larger, single structures.
 - Speedups
 - Improve code readability
 - Include unit tests ([googletest][googtest])
 - Improve documentation

Further long-term goals include:

 - Introduce missing types to the library.
 - Provide packages for common GNU/Linux distributions, and other OSs.
 - Provide the option of installing it as a shared library (easing compilation and updates).
 - Wrappers for popular programming languages.


Links
-----
Some useful project links are below:

 - [LIBCDS 2 GitHub project][gitproject]
 - [LIBCDS 2 Wiki][wiki]
 - [LIBCDS 2 Issues][issues]
 - [Original LIBCDS Site][libcds1]
 - [LIBCDS 2 Developers Google Group][devgroup]


Guidelines
----------

 - When you commit, it is useful to give a good message.

 - The code tries to follow this style guide [C++ Style Guide][cppstyle].

 - Before commiting, please make sure you run all tests and 'make cpplint/indent' to check for style errors.


[libcds1]: http://libcds.recoded.cl/
[devgroup]: http://groups.google.com/group/libcds-dev/
[googtest]: http://code.google.com/p/googletest/
[gitproject]: https://github.com/fclaude/libcds2
[cppstyle]: http://google-styleguide.googlecode.com/svn/trunk/cppguide.xml
[wiki]: https://github.com/fclaude/libcds2/wiki
[issues]: https://github.com/fclaude/libcds2/issues
