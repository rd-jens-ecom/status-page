# status-page
[![Build Status](https://travis-ci.org/fthomas/status-page.svg?branch=master)](https://travis-ci.org/fthomas/status-page)
[![codecov](https://codecov.io/gh/fthomas/status-page/branch/master/graph/badge.svg)](https://codecov.io/gh/fthomas/status-page)
[![Scaladex](https://index.scala-lang.org/fthomas/status-page/latest.svg?color=blue)](https://index.scala-lang.org/fthomas/status-page/status-page-core)
[![Scaladoc](https://www.javadoc.io/badge/eu.timepit/status-page-core_2.12.svg?color=blue&label=Scaladoc)](https://javadoc.io/doc/eu.timepit/status-page-core_2.12)

**status-page** is a microlibrary for creating simple status pages.
It provides data structures and functions to organize, aggregate, and render
status information in a straightforward way.

# Using status-page

The latest version of the library is available for Scala 2.12.

If you're using sbt, add the following to your build:
```sbt
libraryDependencies ++= Seq(
  "eu.timepit" %% "status-page-core" % "<latestVersion>",
  "eu.timepit" %% "status-page-cats" % "<latestVersion>"  // optional
)
```

# License

**status-page** is licensed under the Apache License, Version 2.0, available at
http://www.apache.org/licenses/LICENSE-2.0 and also in the
[LICENSE](https://github.com/fthomas/status-page/blob/master/LICENSE) file.
