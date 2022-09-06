
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

I don’t have a ton in here currently, but the future is bright for these
projects. Here’s a quick overview of the projects I’m working on.

### ezverse <a href='https://github.com/EricLamphere/ezverse'><img src='images/hex_sticker_ezverse.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://lifecycle.r-lib.org/articles/stages.html#maturing)
[![R-CMD-check](https://github.com/EricLamphere/ezverse/actions/workflows/check-release.yaml/badge.svg)](https://github.com/EricLamphere/ezverse/actions/workflows/check-release.yaml)
[![CRAN
status](https://www.r-pkg.org/badges/version/ezverse)](https://CRAN.R-project.org/package=ezverse)
<!-- badges: end -->

I’m working on a collection of packages (all prefixed with ‘ez’) that
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

### Apps <a href='https://github.com/rstudio/shiny'><img src='images/app-store-logo-transparent.svg' align="right" height="139" /></a>

I haven’t gone too far with this yet, but here are the shells of a
couple apps I have in mind:

- 🏘️
  [**whats-the-census**](https://github.com/EricLamphere/whats-the-census.git) -
  R Shiny app that summarises and visualizes data from the census API
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
