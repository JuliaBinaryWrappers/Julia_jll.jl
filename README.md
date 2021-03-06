# `Julia_jll.jl` (v1.5.0+0)

This is an autogenerated package constructed using [`BinaryBuilder.jl`](https://github.com/JuliaPackaging/BinaryBuilder.jl). The originating [`build_tarballs.jl`](https://github.com/JuliaPackaging/Yggdrasil/blob/f6a67233f1bf2b6884776a4ce2f6b6434ba08ab5/J/Julia/build_tarballs.jl) script can be found on [`Yggdrasil`](https://github.com/JuliaPackaging/Yggdrasil/), the community build tree.

For more details about JLL packages and how to use them, see `BinaryBuilder.jl` [documentation](https://juliapackaging.github.io/BinaryBuilder.jl/dev/jll/).

## Sources

The tarballs for `Julia_jll.jl` have been built from these sources:

* compressed archive: https://julialang-s3.julialang.org/bin/linux/aarch64/1.5/julia-1.5.0-linux-aarch64.tar.gz (SHA256 checksum: `6c6f1d3b6d16829e1ecc0528bb8bb15f9fe90b03fcee99509a3fe625cac32c51`)
* compressed archive: https://julialang-s3.julialang.org/bin/linux/x64/1.5/julia-1.5.0-linux-x86_64.tar.gz (SHA256 checksum: `be7af676f8474afce098861275d28a0eb8a4ece3f83a11027e3554dcdecddb91`)
* compressed archive: https://julialang-s3.julialang.org/bin/linux/x86/1.5/julia-1.5.0-linux-i686.tar.gz (SHA256 checksum: `dafefde1fb1387730d804c7b4bb29c904311f0a52b12bf44c0c4ed4af6ae58e6`)
* compressed archive: https://julialang-s3.julialang.org/bin/mac/x64/1.5/julia-1.5.0-mac64.tar.gz (SHA256 checksum: `9c36a4366eafa15b4a3d4533dcd0ab8ed799eab13305f6662eca905e0480fc65`)
* compressed archive: https://julialang-s3.julialang.org/bin/winnt/x64/1.5/julia-1.5.0-win64.tar.gz (SHA256 checksum: `48a0203b7144e04679bec9500c927ef36dd450cfa8d2a9f4517192794eb7c9ba`)
* compressed archive: https://julialang-s3.julialang.org/bin/winnt/x86/1.5/julia-1.5.0-win32.tar.gz (SHA256 checksum: `d0d3bbcb8fa73c1d5e4eacb9e1d4fb3992979fed4056e4051d4a4b04e211268d`)
* compressed archive: https://julialang-s3.julialang.org/bin/freebsd/x64/1.5/julia-1.5.0-freebsd-x86_64.tar.gz (SHA256 checksum: `b07dc5b649828495350ed0729e003aa87da6f91e8a0f06ead9825d533b3d379f`)

## Platforms

`Julia_jll.jl` is available for the following platforms:

* `Linux(:aarch64, libc=:glibc, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`aarch64-linux-gnu-libgfortran4-cxx11`)
* `Linux(:i686, libc=:glibc, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`i686-linux-gnu-libgfortran4-cxx11`)
* `Windows(:i686, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`i686-w64-mingw32-libgfortran4-cxx11`)
* `MacOS(:x86_64, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`x86_64-apple-darwin14-libgfortran4-cxx11`)
* `Linux(:x86_64, libc=:glibc, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`x86_64-linux-gnu-libgfortran4-cxx11`)
* `FreeBSD(:x86_64, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`x86_64-unknown-freebsd11.1-libgfortran4-cxx11`)
* `Windows(:x86_64, compiler_abi=CompilerABI(libgfortran_version=v"4.0.0", cxxstring_abi=:cxx11))` (`x86_64-w64-mingw32-libgfortran4-cxx11`)

## Dependencies

The following JLL packages are required by `Julia_jll.jl`:

* [`Zlib_jll`](https://github.com/JuliaBinaryWrappers/Zlib_jll.jl)

## Products

The code bindings within this package are autogenerated from the following `Products`:

* `ExecutableProduct`: `julia`
* `LibraryProduct`: `libjulia`
