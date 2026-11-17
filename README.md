# BIOS 667 Exam 3, Take-Home Portion

| File | Contents |
|:--|:--|
| [`Exam3-take-home.pdf`](Exam3-take-home.pdf) | Instructions and problems |
| [`sbp_trial.csv`](sbp_trial.csv) | Data for Problem 1 |
| [`asthma_trial.csv`](asthma_trial.csv) | Data for Problem 2 |

The datasets can be read directly into R.

```r
base_url <- "https://raw.githubusercontent.com/daviddaiweizhang/unc-bios667-2026-exam3/main/"
sbp <- read.csv(paste0(base_url, "sbp_trial.csv"))
asthma <- read.csv(paste0(base_url, "asthma_trial.csv"))
```
