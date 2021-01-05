This registry was created using the `LocalRegistry` package via
```jl
LocalRegistry.create_registry("tchrResearch", "https://github.com/thchr/tchrResearch.git"; description="...")
```

To update a package to a more recent version (only possible after incrementing its version number), call `LocalRegistry.register(PkgNameAsString)`, and then push that resulting commit (or set the keyword argument `push=true`).
