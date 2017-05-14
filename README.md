# ExamplePackage

[![Build Status](https://travis-ci.org/ChrisRackauckas/ExamplePackage.jl.svg?branch=master)](https://travis-ci.org/ChrisRackauckas/ExamplePackage.jl)
[![Build status](https://ci.appveyor.com/api/projects/status/9iuvdt0j0mw6au0k?svg=true)](https://ci.appveyor.com/project/ChrisRackauckas/examplepackage-jl)
[![Coverage Status](https://coveralls.io/repos/github/ChrisRackauckas/ExamplePackage.jl/badge.svg?branch=master)](https://coveralls.io/github/ChrisRackauckas/ExamplePackage.jl?branch=master)

This is an example Julia repository. It was generated using:

```julia
# Pkg.add("PkgDev")
using PkgDev
PkgDev.generate("ExamplePackage","MIT")
```

Please check out the source code for details. In the `/src` directory, the general
structure of a Julia package is outlined. Tips and suggestions are given so that
way the library can be both generic and performant. In the `/test` directory,
a scalable testing structure is shown. The `REQUIRE` file shows how to setup
a package dependency. The `/docs` folder was generated using

```julia
# Pkg.add("Documenter")
using Documenter
Documenter.generate("ExamplePackage")
```

Continuous integration (CI) testing will run your test suite every time code is changed.
It will also build a new version of your docs. Setting up CI is mandatory for
any registered Julia package. For information on getting CI setup, see

http://www.stochasticlifestyle.com/finalizing-julia-package-documentation-testing-coverage-publishing/

You should setup both Travis and AppVeyor. Travis is for Linux and Mac, while
AppVeyor is for Windows. This will ensure that your package installs and runs
and the most popular OSs.

## Installing this Package

Since this package is not registered, you must install it by cloning. To add this package, use:

```julia
Pkg.clone("https://github.com/ChrisRackauckas/ExamplePackage.jl")
```

## Performance

For general tips for getting good performance, check out the following post:

http://www.stochasticlifestyle.com/7-julia-gotchas-handle/
