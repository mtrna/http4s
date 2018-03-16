# Http4s [![Build Status](https://travis-ci.org/http4s/http4s.svg?branch=master)](https://travis-ci.org/http4s/http4s) [![Build status](https://ci.appveyor.com/api/projects/status/aprulmaagd5u1705?svg=true)](https://ci.appveyor.com/project/ChristopherDavenport/http4s-m0hqu) [![Gitter chat](https://badges.gitter.im/http4s/http4s.png)](https://gitter.im/http4s/http4s) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.http4s/http4s-core_2.12/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.http4s/http4s-core_2.12) [![Typelevel library](https://img.shields.io/badge/typelevel-library-green.svg)](http://typelevel.org/projects/#http4s)

Http4s is a minimal, idiomatic Scala interface for HTTP services.  Http4s is
Scala's answer to Ruby's Rack, Python's WSGI, Haskell's WAI, and Java's
Servlets.

```scala
val service = HttpService {
    case GET -> Root / "hello" =>
      Ok("Hello, better world.")
  }
```

Learn more at [http4s.org](http://http4s.org/).

If you run into any difficulties please enable partial unification in your `build.sbt`

```scala
scalacOptions ++= Seq("-Ypartial-unification")
```

## Code of Conduct

http4s is proud to be a [Typelevel](http://typelevel.org/) incubator
project.  We are dedicated to providing a harassment-free community
for everyone, and ask that the community adhere to the
[code of conduct](http://typelevel.org/conduct.html).

## License

This software is licensed under the Apache 2 license, quoted below.

> Copyright 2013-2017 http4s [[http://http4s.org](http://http4s.org/)]

> Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

> [[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)]

> Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Acknowledgments

[![YourKit](https://www.yourkit.com/images/yklogo.png)](https://www.yourkit.com/)

Special thanks to [YourKit](https://www.yourkit.com/) for supporting this project's ongoing performance tuning efforts with licenses to their excellent product.
