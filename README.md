# Scraper

Learning to use python by writing a scraper for [Andrew Gelman](http://www.stat.columbia.edu/~gelman/)'s blog, based on [this New Year's post](https://statmodeling.stat.columbia.edu/2022/01/01/most-controversial-posts-of-2021/) 🎉. Try it out!

## The first csv file looks like this:

2021 Blog
| Post Title  | Post Date | Unique Commenters | URL |
| ----------- | ----------- | :----:  | ----------- |
| **What we did in 2020, and thanks to all our collaborators and many more** | 2021-01-01 | 12 | https://statmodeling.stat.columbia.edu/2021/01/01/what-we-did-in-2020/#comments |
| **Typos of the day** | 2021-01-04 | 4 | https://statmodeling.stat.columbia.edu/2021/01/05/typo-of-the-day/#comments |
| **xkcd: "Curve-fitting methods and the messages they send"** | 2021-01-07 | 28 | https://statmodeling.stat.columbia.edu/2021/01/07/xkcd-curve-fitting-methods-and-the-messages-they-send/#comments |

## The second csv file looks like this:

2021 Commenters
| Commenters  | Total Response Rate | Number of Posts |
| ----------- | ----------- | ----------- |
| Jane Smith | 286 | 88 |
| Jane Doe | 1089 | 162 |

## The data visualizations (from Gelman's annual charts) look like this:
![Histogram](/histogram.png)

![Scatterplot](/scatterplot.png)
