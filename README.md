Giter8 Flink project template
=============================

This is [giter8](https://github.com/n8han/giter8) template to generate a [Flink](http://flink.apache.org) project using Scala and SBT.

How to use
----------

First you have to install [giter8](https://github.com/n8han/giter8).
See the [installation description](https://github.com/n8han/giter8#installation) for further information.

In order to generate a Flink project enter on the command line:

```
$ g8 tillrohrmann/flink-project
````

This will generate a Flink project using Scala and SBT.

Run job from IntelliJ
---------------------

In order to run your job from within IntelliJ, you have to set the classpath in the run/debug configuration to the module `mainRunner`.
Simply open `Run -> Edit configurations...` and then select `mainRunner` from the "Use classpath of module" dropbox.


