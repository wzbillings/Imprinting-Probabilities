# Calculating Imprinting Probabilities

In this repo, I use the method of Gostic 2016 and Arevalo 2020 in order to calculate a table of HA imprinting probabilities for H1N1, H2N2, and H3N2 subtypes.

**Update**: now that the [imprinting](https://cran.r-project.org/web/packages/imprinting/imprinting.pdf) R package is released, I do not plan to keep working on this.

## TODO

* [ ] Determine how the 2009.5 datum was calculated for Arevalo 2020 and check if this data point is specifically included in Gostic 2016.
* [x] Create bibliography and add to .Rmd file.
* [x] Baseline attack rate calculation
* [x] Seasonal intensity
* [ ] Fraction of season experienced
  * [ ] Need to figure out how division by zero was handled.
  * [ ] Details on $p$ calculations?
* [ ] time-varying per-season infection probability
* [ ] individual time-varying probability of infection
* [ ] fraction unexposed
* [ ] frequency of subtypes
* [ ] imprinting probabilities
