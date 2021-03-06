
# StatPlots.jl NEWS

## 0.5 current version

### 0.5.0
- major reconfiguring of the support for tables:
    - change the syntax to `@df mydataframe plot(:a, :b)`
    - allows using DataFrames automatically in user recipes
    - support for all iterable tables, including DataFrame, DataTable, IndexedTable, IterableTable and DataStreams.Source
- better interface to `groupedbar`
- added equal-area histograms
- added the `:wand` binning option for 1-dimensional histograms

### 0.4.2
- improvements to the groupapply function

### 0.4.1
patch release
- reexport Plots

### 0.4.0
- Fix 0.6 deprecations
- support for `_cycle`

### 0.3.0
- added expressions with DataFrame symbols
- added `groupapply` method for population analysis
- updated boxplots to turn off outlier points and improves whiskers
