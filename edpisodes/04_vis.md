Visualization
================
John Little
2019-07-11

<!-- README.md is autogenerated from README.Rmd.  Please only edit README.Rmd -->

Very **simple** visualizations

  - grammar of graphics

  - Two Variable scatter plot
    
      - continuous and discrete
      - geom\_plot(aes(x = height, y = mass))
      - geom\_plot(aes(x = height, y = mass, size = year))
      - geom\_plot(aes(x = height, y = mass, color = gender))
      - geom\_plot(aes(x = height, y = mass), size = 4, color =
        “dodgerblue”))

  - Categorical Data
    
      - forcats is a must `fct_infreq`
    
      - stringr and regex is gonna show up
        
          - `str_count`
          - `str_replace()`

## Advanced

First, [effective
visualizations](https://www.geckoboard.com/learn/data-literacy/data-visualization-tips/)

### Dashboards

  - See `flexdashboards`
  - See `HTML Widgets`

### Interactivity

  - See `ggplotly`
  - See `Shiny`
