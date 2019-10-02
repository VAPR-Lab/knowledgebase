## VAPR Lab Knowledge Base

<h1 align="center">
  <br/><img src="images/VAPR-brand-banner.png"><br />
  </h1>
  
### AN INTERDISCIPLINARY LAB FOR BOUNDARY-PUSHING SCHOLARSHIP
<br />

This "lab," for lack of a better word, lives online and serves as a place for like-minded explorers to pool their interests and skills, creating work and products that could never have arisen in silos.<sup>[1](#footnote1)</sup>

This readme is basically the meta information for the knowledgebase book. More forward-facing announcements and updates from the lab can be found on the website.

## How Tos

Some things that always seem to fade from memory or just need an easy copy-paste source.

### Including graphics

Graphics can be included inline with the following code as the bookdown files are written in RMarkdown:

```r
knitr::include_graphics(rep("images/VAPR-brand-banner.png"))
```

Note that this can be either a local, relative file or a URL.

### Adding Tweets, Videos, Etc

The standard shortcodes don't work when building in R. Use the following inline R code template for including these kinds of files:

```r
blogdown::shortcode('tweet', '1098597896256143365')
```

Gives you an embedded version of [this tweet](https://twitter.com/RyanStraight/status/1098597896256143365).

You can pick from a variety of sources like `youtube` and `instagram` and `vimeo`.

### Knitting/publishing

This is constructed using the [Bookdown](https://bookdown.org) package. The following console commands are used to easily built the book in HTML, PDF, and ePub formats simultaneously.

``` r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
bookdown::render_book("index.Rmd", "bookdown::epub_book")
```

This is an ongoing and unfinished work of passion!

<hr>

<sub><a name="footnote1">1</a>: Note the lack of the word *synergy*. Terrible word.</sub>
