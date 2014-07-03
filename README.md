GraphLayout.jl
==============

Graph layout algorithms in pure Julia. Currently only has the spring-based method of [Fruchterman and Reingold (1991)](http://www.mathe2.uni-bayreuth.de/axel/papers/reingold:graph_drawing_by_force_directed_placement.pdf), but more can and will be added. Only other restriction is the graph must be provided in adjacency matrix format - adjacency list and [Graph.jl](https://github.com/JuliaLang/Graphs.jl) support to come later (PRs welcomed).

If you have [Compose.jl](https://github.com/dcjones/Compose.jl) installed you can also plot the resulting graphs:

![Pentagon](https://rawgit.com/IainNZ/GraphLayout.jl/master/test/pentagon.svg)

![Random](https://rawgit.com/IainNZ/GraphLayout.jl/master/test/random.svg)

![Gadfly](https://rawgit.com/IainNZ/GraphLayout.jl/master/example/gadfly.svg)

MIT License. Copyright (c) 2014 Iain Dunning
