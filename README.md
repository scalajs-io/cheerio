Cheerio API for Scala.js
================================
This is a Scala.js type-safe binding for [Cheerio](https://www.npmjs.com/package/cheerio).

A tiny, fast, and elegant implementation of core jQuery designed specifically for the server.

<a name="build_requirements"></a>
#### Build Requirements

* [ScalaJs.io v0.3.x](https://github.com/ldaniels528/scalajs.io)
* [SBT v0.13.13](http://www.scala-sbt.org/download.html)

<a name="building_sdk"></a>
#### Build/publish the SDK locally

```bash
 $ sbt clean publish-local
```

<a name="resolvers"></a>
#### Resolvers

To add the Cheerio binding to your project, add the following to your build.sbt:  

```   
resolvers += Resolver.sonatypeRepo("releases") 
```