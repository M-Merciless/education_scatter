# education_scatter
[Comparison of Budgeted Education Revenue and Outturn Expediture in Wales ](https://richleysh84.shinyapps.io/education_combined_scatter_v3/?_ga=2.10999540.1956124142.1597647415-1514404761.1589466128)

This simple shiny interface is a proof of concept. Feel free to use and repurpose / improve. I'd love to get any feedback you have, too.

All source data comes from the stats wales website, please follow the link at the bottom of the interactive charts to view.

The first tab compares budgeted education revenue and education outturn expenditure data for schools in all educational phases. The moset recent, common financial year's data is available on this tab (budgeted is published a year in advance of outturn). The datasets are presented on 2 different chars, due to limitations in comparing like for like between budgeted and outturn - some of the budget areas are not reported consistently and direct comparison between the 2 datasets should be done cautiously.

The smoothing curve should not really be used to identify outliers, but is a confidence interval at 95% certainty for the true position of the mean. It is to be interpreted as a measure of central tendency of the model as a whole, rather than in regards to any one particular datum.You will notice that as the number of observations decrease, the 95 % confidence interval range also increases.

The second tab allows the user to select from any local authority and school in Wales, and then renders all available time series data for that school. This tab can access budgeted and outturn data. 

Many thanks for taking a look and I hope you find the code useful. 

