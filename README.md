ScalaZ3 for Scala 2.10, 2.11, and 2.12
======================================

This is ScalaZ3 for Z3 4.5.0 and Scala 2.10, 2.11, and 2.12.

ScalaZ3 for Z3 version 4.3.2 can be found in the branch `Z3-4.3.2`.

Switch to the branch `2.9.x` for Scala 2.9 support (Z3 version 4.3.2).

Compiling ScalaZ3
=================

You should have Java and SBT 0.13.x installed.

Mac & Unix
----------

Run

    sbt +package
    
to compile Z3 4.5.0 and cross-compile ScalaZ3 for Scala 2.10, 2.11 and 2.12.

The JAR files will be in `target/scala-2.XX/scalaz3_2.XX-3.0.jar`
and will contain the shared library dependencies.

For testing, run

    sbt +test

Windows
-------

Install Visual Studio Community edition 2015
Make sure to have the following:
- Programming Languages
  - Visual C++
    - Common tools for Visual C++ 2015 (CHECK)

Open the native x64 command prompt (available in the start menu under the Visual Studio folder)

Now navigate to the scalaz3 folder and type:

    sbt +package

The JAR files will be in `target/scala-2.XX/scalaz3_2.XX-3.0.jar` and will contain the shared library
dependencies.
