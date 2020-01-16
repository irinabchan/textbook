# Setting up Julia

This project was developed using [Julia][julia] v1.2.0, which can be found for download [here][old_releases], and [Jupyter Notebook][jupyter].

Below are the modules and packages used during development. Generally, to install a package on the REPL:
```julia
julia> using Pkg
julia> Pkg.add("ModuleName")
```
Please refer to the documentation pages for further information.

|Module| Documentation |
|--|--|
| CategoricalArrays.jl | https://juliadata.github.io/CategoricalArrays.jl/stable/ |
| CSV.jl | https://juliadata.github.io/CSV.jl/stable/ |
| DataFrames.jl | https://juliadata.github.io/DataFrames.jl/stable/ |
| Distributions.jl | https://juliastats.org/Distributions.jl/stable/index.html |
| Flux.jl | https://fluxml.ai/Flux.jl/stable/ |
| HTTP.jl | https://juliaweb.github.io/HTTP.jl/stable/ |
| IJulia.jl | https://github.com/JuliaLang/IJulia.jl |
| Images.jl | https://juliaimages.org/latest/ |
| Interact.jl | https://juliagizmos.github.io/Interact.jl/stable/ |
| JSON.jl | https://github.com/JuliaIO/JSON.jl |
| KernelDensity.jl | https://github.com/JuliaStats/KernelDensity.jl |
| LaTeXStrings.jl | https://pkg.julialang.org/docs/LaTeXStrings/H4HGh/1.0.3/ |
| MLDataUtils.jl | https://mldatautilsjl.readthedocs.io/en/latest/index.html |
| MLJ.jl | https://alan-turing-institute.github.io/MLJ.jl/stable/ |
| MLJLinearModels.jl | https://github.com/alan-turing-institute/MLJLinearModels.jl |
| MLJModels.jl | https://github.com/alan-turing-institute/MLJModels.jl |
| Optim.jl | https://github.com/JuliaNLSolvers/Optim.jl |
| Polynomials.jl | https://juliamath.github.io/Polynomials.jl/stable/ |
| PyCall.jl | https://github.com/JuliaPy/PyCall.jl |
| RDataSets.jl | https://github.com/JuliaStats/RDatasets.jl |
| ROCAnalysis.jl | https://github.com/davidavdav/ROCAnalysis.jl/ |
| ScikitLearn.jl | https://scikitlearnjl.readthedocs.io/en/latest/ |
| StatsBase.jl | https://juliastats.org/StatsBase.jl/stable/ |
| Suppressor.jl | https://github.com/JuliaIO/Suppressor.jl |
| TextAnalysis.jl | https://juliatext.github.io/TextAnalysis.jl/latest/ |
| ZipFile.jl | https://github.com/fhs/ZipFile.jl |

[julia]: https://docs.julialang.org/en/v1/
[old_releases]: https://julialang.org/downloads/oldreleases/
[jupyter]: https://jupyter.org/