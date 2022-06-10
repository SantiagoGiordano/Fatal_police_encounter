
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Mapping Fatal Police Encounters by State

<!-- badges: start -->
<!-- badges: end -->

Which US states have the highest per capita fatal police encounters ?

![](README_files/figure-gfm/log-fig-1.png)<!-- -->

-   An important note is the map above uses a logged scale for
    fatalities per 100,000 people. Due to Wyoming being an outlier
    state - with over double the number per capita fatalities as the
    second closest state - it is visually challenging to discern any
    significant variation among other states when a leveled scale is
    used. This issue can be seen in the map plotted below. Conversely,
    the variation among states is more apparent when using a logged
    scale: we can see in which states the fatalities are lower as a
    proportion to population and where they are higher. The downside to
    the log scale is the lack of interpretability of the scale. By
    comparing the legends from the two maps, we can generally assume the
    log scale indicates how many times larger the fatality rate is in a
    given state from the state with the lowest rate.

![](README_files/figure-gfm/levels-fig-1.png)<!-- -->

## Source

Data from [fatalencounters.org](https://fatalencounters.org)
