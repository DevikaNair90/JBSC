---
title: The Julia Ecosystem
date: 2019-09-30
---
These are some packages I recommend for various features and applications

These are not the universe of the Julia ecosystem by any means

I include only packages that I have extensively used and can vouch that these are production-ready maintained and of high quality (doesn't mean perfect)

These are limited to quite general use and to end-users

- Benchmarking ([BenchmarkTools.jl](https://github.com/JuliaCI/BenchmarkTools.jl))
- Combinatorics ([Combinatorics.jl](https://github.com/JuliaMath/Combinatorics.jl))
- Data Storage, and Manipulation
    - Tabular structure ([DataFrames.jl](https://github.com/JuliaData/DataFrames.jl))
    - Interpolation ([Interpolations.jl](https://github.com/JuliaMath/Interpolations.jl))
    - SQL Databases ([LibPQ.jl](https://github.com/invenia/LibPQ.jl))
- Date and Time: [Dates.jl](https://docs.julialang.org/en/latest/stdlib/Dates/index.html) + [TimeZones.jl](https://github.com/JuliaTime/TimeZones.jl)
- Distances ([Distances.jl](https://github.com/JuliaStats/Distances.jl))
- Distributions ([Distributions.jl](https://github.com/JuliaStats/Distributions.jl))
- HyperText Transfer Protocol (HTTP) ([HTTP.jl](https://github.com/JuliaWeb/HTTP.jl))
- GraphQL Client: [Diana.jl](https://github.com/codeneomatrix/Diana.jl)
- Input/Output (I/O)
    - Delimited Text Files (DSV) ([CSV.jl](https://github.com/JuliaData/CSV.jl))
    - R ([RData.jl](https://github.com/JuliaData/RData.jl))
    - Tom's Obvious, Minimal Language (TOML) (`Pkg.TOML.parsefile`)
    - JavaScript Object Notation (JSON) ([JSON3.jl](https://github.com/quinnj/JSON3.jl))
    - Portable Document Format (PDF) ([PDFIO.jl](https://github.com/sambitdash/PDFIO.jl))
    - Datasets from R ([RDatasets.jl](https://github.com/johnmyleswhite/RDatasets.jl))
- Integrated Development Environment (IDE)
    - [Atom](https://atom.io/): [Atom.jl](https://github.com/JunoLab/Atom.jl) / [Juno.jl](https://github.com/JunoLab/Juno.jl)
    - [Jupyter](https://jupyter.org/): [IJulia.jl](https://github.com/JuliaLang/IJulia.jl)
    - [Visual Studio Code](https://www.julia-vscode.org/)
- Optimization ([Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl))
- Plotting ([Plots.jl](https://github.com/JuliaPlots/Plots.jl) + [StatPlots.jl](https://github.com/JuliaPlots/StatPlots.jl))
- Statistics
    - Generalized Linear Models ([GLM.jl](http://juliastats.github.io/GLM.jl/stable/))
    - Hypotheses Testing ([HypothesisTests.jl](http://juliastats.github.io/HypothesisTests.jl/latest/))
    - Linear Mixed Models ([MixedModels.jl](https://github.com/dmbates/MixedModels.jl))
    - Econometrics ([Econometrics.jl](https://github.com/Nosferican/Econometrics.jl))
