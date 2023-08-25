# Registry

This is a private registry of projects by itsdfish.

## Using This Registry

To use this registry, paste the following into the REPL:

```julia
using Pkg
pkg"registry add https://github.com/itsdfish/Registry.jl"
```

## Installing Packages

Once you have installed the registry, installing packages works the same way as the General registry in Julia. Enter the package mode with `]` and type:

```julia
add SocialSamplingTheory
```
or `add` followed by the name of the package you would like to install. 

# More Info

For more information on registries, see [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl)