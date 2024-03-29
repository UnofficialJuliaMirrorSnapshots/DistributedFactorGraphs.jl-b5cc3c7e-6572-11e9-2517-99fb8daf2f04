## Function Reference

```@contents
Pages = [
    "func_ref.md"
]
Depth = 3
```

### Graph Types
```@docs
GraphsDFG
```

### Creating DFG Factor Graphs
```@docs
addVariable!
addFactor!
```

### Getting Factor Graph Nodes
```@docs
getVariables
getFactors
getVariable
getFactor
getNeighbors
ls
lsf
```

### Updating Factor Graph Nodes
```@docs
updateVariable!
updateFactor!
```

### Deleting Factor Graph Nodes
```@docs
deleteVariable!
deleteFactor!
```

### Getting Adjacency Matrix
```@docs
getAdjacencyMatrix
```

### Validating Factor Graph Connectivity
```@docs
isFullyConnected
hasOrphans
```

### Copying Subgraphs
```@docs
getSubgraphAroundNode
getSubgraph
```

### Summaries
```@docs
getSummary
getSummaryGraph
```

### Visualization and Plotting
```@docs
toDot
toDotFile
dfgplot
```
