
# Welcome 👋

Hayo, welcome to my GitHub 🐙 ! Here you’ll find a myriad of random
things I’m working on. **Before you move on**, there’s one important
thing you should know…

![](images/i_understand_nothing.gif) <!--
![](https://media.giphy.com/media/SAAMcPRfQpgyI/giphy.gif)
-->

That said, if you have any questions, want to collaborate on a project,
or find an issue with my code, feel free to submit an issue in GitHub or
hit me up at any of the following:

- [LinkedIn](https://www.linkedin.com/in/ericjlamphere/) - I’m
  relatively active on linkedIn, so if we work together on something,
  let’s connect
- [Email](mailto:ericjlamphere@gmail.com) - Most likely to get a
  response
- [Twitter](https://twitter.com/ericlamphere) - I don’t really use it a
  ton, but you can send me cool things or questions here and I’ll see
  them eventually

# Projects 🤖

Random things I've worked on over the years. 

> [!NOTE]
> Recently (along with every other programmer in the world..) I've been using AI to help me write code. Claude Code is my goto so you'll see some `CLAUDE.md` and `.claude/*` files in the repos where I use it. That said, I make a point to read and understand all of the code that AI generates for me. Otherwiswe, what's the point?

### ezverse <a href='https://github.com/EricLamphere/ezverse'><img src='images/hex_sticker_ezverse.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://lifecycle.r-lib.org/articles/stages.html#maturing)
[![R-CMD-check](https://github.com/EricLamphere/ezverse/actions/workflows/check-release.yaml/badge.svg)](https://github.com/EricLamphere/ezverse/actions/workflows/check-release.yaml)
[![CRAN
status](https://www.r-pkg.org/badges/version/ezverse)](https://CRAN.R-project.org/package=ezverse)
<!-- badges: end -->

A collection of packages (all prefixed with ‘ez’) that
are supposed to make various aspects of data science and analytics
engineering much ~~ez~~easier. Current state looks like this:

- [**ezxfig**](https://github.com/EricLamphere/ezxfig.git) - Easily
  transform data frames
  - “xfig” comes from the word “transfigure”, meaning “transform into
    something more beautiful or elevated”. Kind of lame but I liked it
- [**ezexplore**](https://github.com/EricLamphere/ezexplore.git) -
  Easily explore data sets and produce summary statistics
- [**ezviz**](https://github.com/EricLamphere/ezviz.git) - Easily
  configure `formattable` tables for aesthetically pleasing table output
- [**ezextras**](https://github.com/EricLamphere/ezextras.git) -
  Intuitive, easy to use helper functions to make for faster development
  and more readable code
- [**ezverse**](https://github.com/EricLamphere/ezextras.git) - Easily
  install and load all of the `ezverse` packages

Similar to the `tidyverse`, you can install and load all of the
`ezverse` packages with:

``` r
remotes::install_github("EricLamphere/ezverse")
```

### Central Database

The big idea: Set up my own server on a Raspberry Pi that I can use as a central database for all of my future projects. I've started a project with clickhouse but I haven't landed on that as my platform of choice yet. 

- 🍋
  [**clickhouse-db**](https://github.com/EricLamphere/clickhouse-db.git) -
  ClickHouse database that could be used as the database for future
  projects. I don’t have any experience with ClickHouse or Airflow, so I
  wanted to see if I could get those things working together in a docker
  container.
  - Database: ClickHouse
  - Orchestration: Airflow
  - ETL & ELT: dbt
  - Packaging: Docker

### Apps <a href='https://github.com/rstudio/shiny'><img src='images/app-store-logo-transparent.svg' align="right" height="139" /></a>

#### Actually Functional

- 🏖️ [**survivor**](https://github.com/EricLamphere/survivor.git) - R
  Shiny app for keeping track of the survivor pool that I set up with my
  family and friends

#### Ideas

I haven’t gone too far with these yet, and I maybe never will, but here are the shells of a
couple apps I have in mind:

- ⚽
  [**better-bets**](https://github.com/EricLamphere/better-bets.git) -
  An app for providing predictive analytics (via. the [Football
  Prediction
  API](https://rapidapi.com/boggio-analytics/api/football-prediction/)
  from [RapidAPI](https://rapidapi.com/hub)) for upcoming soccer games
  with the end goal of a more profitable and consistent betting system.
  Here’s my vision for the stack:
  - Front-end: React
  - Web framework: Flask
  - API: GraphQL (Graphene)
  - Database: MongoDB (mongomock)
- 🏘️
  [**whats-the-census**](https://github.com/EricLamphere/whats-the-census.git) -
  R Shiny app that summarises and visualizes data from the census API
