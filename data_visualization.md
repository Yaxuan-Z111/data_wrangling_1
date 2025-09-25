Visualization
================
yz5248
2025-09-25

import the weather data

``` r
data("weather_df")
```

making our first plot :-)

``` r
ggplot(data = weather_df, mapping = aes(x = tmin, y = tmax)) + 
  geom_point()
```

    ## Warning: Removed 17 rows containing missing values or values outside the scale range
    ## (`geom_point()`).

![](data_visualization_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->
