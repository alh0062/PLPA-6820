``` r
library(knitr)
library(ggplot2)
#library(markdown)
```

``` r
data("mtcars")
ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_smooth(method = lm, se = FALSE) +
  geom_point(aes(color = wt)) +
  xlab("Weight") + 
  ylab("Miles per gallon") +
  scale_colour_gradient(low = "forestgreen", high = "black")
```

    ## `geom_smooth()` using formula = 'y ~ x'

![](Neff_HWMarkdown_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

``` r
## `geom_smooth()` using formula = 'y ~ x'
```

## R Headers

# First-level header

`*italic*` \## Second-level header

### Third-level header
