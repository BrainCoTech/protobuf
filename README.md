Protobuf runtime support library
================================

This library provides runtime support library for Dart implementation
of protobufs.

Typically one do not need to import this library---only libraries
generated by protoc plugin import this library directly.

However, if your library or application uses generated protobuf libraries,
please, add this library as a dependency.

Hacking
-------

So far to hack on the library the main thing you should be aware of is how
to run unittests.  The easiest way would be to use DartEditor and run
`all_tests.dart` file which is the whole suite.

If you'd like to run test from command line, please, do not pass proper
package root.

Useful references
-----------------

* [Main Dart site](http://www.dartlang.org)
* [Main protobuf site](https://code.google.com/p/protobuf)
* [Protoc plugin project](https://github.com/dart-lang/dart-protoc-plugin)
* [DartEditor download](http://www.dartlang.org)
* [Pub documentation](http://pub.dartlang.org/doc)
