## VAPR Lab Knowledge Base

<h1 align="center">
  <br/><img src="images/VAPR-brand-banner.png"><br />
  </h1>
  
### AN INTERDISCIPLINARY LAB FOR BOUNDARY-PUSHING SCHOLARSHIP
<br />

This "lab," for lack of a better word, lives online and serves as a place for like-minded explorers to pool their interests and skills, creating work and products that could never have arisen in silos.<sup>[1](#footnote1)</sup>

## How Tos

### Knitting/publishing

This is constructed using the [Bookdown](https://bookdown.org) package. The following console commands are used to easily built the book in HTML, PDF, and ePub formats simultaneously.

``` r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
bookdown::render_book("index.Rmd", "bookdown::epub_book")
```

This is an ongoing and unfinished work of passion!

<a name="footnote1">1</a>: Note the lack of the word *synergy*. Terrible word. 
