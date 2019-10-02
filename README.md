## VAPR Lab Knowledge Base

<h1 align="center">
  <br>![Banner](images/VAPR-brand-banner.png)
  </h1
  
### AN INTERDISCIPLINARY LAB FOR BOUNDARY-PUSHING SCHOLARSHIP

This "lab," for lack of a better word, lives online and serves as a place for like-minded explorers to pool their interests and skills, creating work and products that could never have arisen in silos.^[Note the lack of the word *synergy*. Terrible word.] 

## How Tos

### Knitting/publishing

This is constructed using the [Bookdown](https://bookdown.org) package. The following console commands are used to easily built the book in HTML, PDF, and ePub formats simultaneously.

``` r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
bookdown::render_book("index.Rmd", "bookdown::pdf_book")
bookdown::render_book("index.Rmd", "bookdown::epub_book")
```

This is an ongoing and unfinished work of passion!
