# 23-143-D-INSPIRES-B

The repository contains two datasets:
1) Circumarctic map
2) Plant taxa of Spitzbergen, derived from GBIF (see references)

Tasks:

Create a multi-panel figure with:
* a) plant occurrences on a map (summarise locations if needed)
* b) a representation of phylogenetic relationships (based on information of the dataset or additional open source data)
* d) Changes in species diversity over time (years)


## Starting point

In R, you can read/import the GBIF data using the `fread` function from the R package `data.table`.

```
gbif <- data.table::fread("Spitzbergen_PlantTaxa/occurrence.txt", sep = "\t", header = TRUE)
```


## References

GBIF.org (13 April 2023) GBIF Occurrence Download  https://doi.org/10.15468/dl.wh8kmw