wk2-workshop
================
Tan Kia Hwee. Beatrice
2024-01-24

- [R Markdown](#r-markdown)

## R Markdown

``` r
stocks_data = readRDS("C:/Users/Beatrice NUS/Y3 Sem 2/DSE3101/Github projects/hello-world/data/wk2_stocks.rds")

paste("The cumulative returns of the S&P index during this period is", as.character(round(sum(stocks_data$SPY_returns), 2)))
```

    ## [1] "The cumulative returns of the S&P index during this period is 2.18"

``` r
paste("The average daily returns of the S&P index during this period is", as.character(round(mean(stocks_data$SPY_returns), 2)))
```

    ## [1] "The average daily returns of the S&P index during this period is 0"

``` r
paste("The standard deviation of the daily returns of the S&P index during this period is", as.character(round(sd(stocks_data$SPY_returns), 2)))
```

    ## [1] "The standard deviation of the daily returns of the S&P index during this period is 0.01"
