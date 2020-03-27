# Julia_example_package.jl

[![Build Status](https://travis-ci.org/ChrisRackauckas/ExamplePackage.jl.svg?branch=master)](https://travis-ci.org/ChrisRackauckas/ExamplePackage.jl)
[![Build status](https://ci.appveyor.com/api/projects/status/9iuvdt0j0mw6au0k?svg=true)](https://ci.appveyor.com/project/ChrisRackauckas/examplepackage-jl)
[![Coverage Status](https://coveralls.io/repos/github/ChrisRackauckas/ExamplePackage.jl/badge.svg?branch=master)](https://coveralls.io/github/ChrisRackauckas/ExamplePackage.jl?branch=master)

**This is an example Julia repository testing Julia package + Compose_demo.jl.**

It was generated using:

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

