## Dataset

🦉 [**Wikipedia page view dataset (2024)**](https://doi.org/10.5281/zenodo.17070469) (15.95 GB) | **Source**: [Analytics datasets: Pageviews](https://dumps.wikimedia.org/other/pageviews/readme.html)

<br>

### Data Files

Each monthly subset captures traffic for approximately 3 million unique pages, resulting in 2 billion discrete data points per month. 

> By utilizing the Parquet columnar format, the high-dimensional data is compressed to a manageable footprint of approximately 1.3 GB per file/month. This highlights the efficiency of binary storage formats for large-scale time series data.

<br>

| Time           | Data file name        | Size    | Wiki pages | Data points | Zero points |
|----------------|-----------------------|---------|------------|-------------|-------------|
| January 2024   | data-202401.parquet   | 1.49 GB | 3,031,046  | 2.25 B      | 24.38%      |
| February 2024  | data-202402.parquet   | 1.43 GB | 3,032,833  | 2.11 B      | 25.01%      |
| March 2024     | data-202403.parquet   | 1.44 GB | 2,918,686  | 2.17 B      | 24.53%      |
| April 2024     | data-202404.parquet   | 1.39 GB | 2,951,902  | 2.13 B      | 24.69%      |
| May 2024       | data-202405.parquet   | 1.34 GB | 2,854,164  | 2.12 B      | 24.58%      |
| June 2024      | data-202406.parquet   | 1.22 GB | 2,671,128  | 1.92 B      | 24.52%      |
| July 2024      | data-202407.parquet   | 1.27 GB | 2,624,815  | 1.95 B      | 24.44%      |
| August 2024    | data-202408.parquet   | 1.28 GB | 2,659,168  | 1.98 B      | 24.30%      |
| September 2024 | data-202409.parquet   | 1.26 GB | 2,706,142  | 1.95 B      | 24.59%      |
| October 2024   | data-202410.parquet   | 1.30 GB | 2,751,244  | 2.05 B      | 24.54%      |
| November 2024  | data-202411.parquet   | 1.25 GB | 2,743,321  | 1.98 B      | 24.64%      |
| December 2024  | data-202412.parquet   | 1.27 GB | 2,625,481  | 1.95 B      | 24.10%      |

<br>

### Time Series Demonstration

While human mobility exhibits clear regularity in **hourly**, **daily**, and **weekly cycles**, the greatest challenge lies in accurately modeling these patterns. In addition, as shown in Figure 1, Wikipedia page view time series also demonstrate periodic patterns across multiple cycles.

<br>

<p align="center">
<img align="middle" src="https://github.com/xinychen/integers/blob/main/graphics/page_view_heatmap.png" width="350" />
</p>

<p align = "center"> <b>Figure 1</b>. Hourly time series of number of views on the 3-million Wikipedia page data in January 2024. These views are up to 72% of the total Wikipedia page views.</p>

<br>

### Support

- For any questions and feedback, please contact Dr. Xinyu Chen (chenxy346@gmail.com).
- If you like this repository, share it with your friends and colleagues.

<br>
