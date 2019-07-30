# osgi-apache-commons-math

An OSGI repository for the popular Apache Commons Math library from http://commons.apache.org/proper/commons-math/

This repository provides an OSGI plugin repository for the Apache
Commons Math library.  The source code has not been modified in any
way. The repository is merely a convenient packaging format for both
the binary and related source material for OSGI developers.

## Install

The most recent version of the library included in the repository is
for Commons Math **3.6.1** and can be installed using Eclipse's plugin
manager.

Add the following URL to the list of available software sites in
eclipse.

```
https://raw.githubusercontent.com/wiki/markroyer/osgi-apache-commons-math/org.apache.commons.math.repository/updates
```

## Building

The project can be built most easily using maven from the
`org.apache.commons.math.parent` directory. Typing

```bash
mvn clean verify
```

will compile the project and create a repository containing all of the
related libraries in

```bash
../../osgi-apache-commons-math.wiki/
```

## LICENSE

The license is the Apache License Version 2.0.  See the included LICENSE file for details.

## Thanks

The library was written by a number of developers at the Apache Software Foundation. For more information, please see [The Apache Commons Math Team](http://commons.apache.org/proper/commons-math/team-list.html).

The ant build scripts are based on code from:

[http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/](http://www.lorenzobettini.it/2015/01/creating-p2-composite-repositories-during-the-build/)

<!--  LocalWords:  osgi apache mvn
 -->
