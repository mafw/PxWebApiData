

## PxWebApiData	0.7.0

* `makeNAstatus`, new parameter to `ApiData` which represents new functionality.
  - When missing entries in `value`, the function tries to add an additional variable, named `NAstatus`, with status codes.


## PxWebApiData	0.6.0

* Changes to meet CRAN policy:
  - *Packages which use Internet resources should fail gracefully with an informative message if the resource is not available or has changed (and not give a check warning nor error).*

## PxWebApiData	0.5.0

* Possible to return a single data set as a data frame: First, second or both combined. 
  - Handled by the new parameter `returnDataSet`. Possible non-NULL values are `1`, `2` and `12`. 
  - New wrapper functions. Function names ending with `1`, `2` or `12`.

  
##  PxWebApiData	0.4.0

* Last version before any news
