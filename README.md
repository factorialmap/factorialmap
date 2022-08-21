# <p align=center>MARCELO CARVALHO DOS ANJOS</p>

## <p align=center>Researcher, prof. of process improvement and surfer</p>


#### :bulb: What am I up to?
>- Using the concept of learning by doing and addressing topics on everyday life in the industry. I try to facilitate research for sulutions using a simplified language
>- Usando o conceito de aprender fazendo e abordando temas diversos do dia a dia na industria procuro facilitar a pesquisa por soluções usando uma linguagem simplificada

#### :runner: Experience
>- 2016-2021 - Business Analyst, researcher, prof. of process improvment and small ivestor
>- 2014-2016 - Business Intelligence and Process Improvement analyst
>- 2011-2012 - Business Intelligence Analyst
>- 2008-2010 - Business Intelligence and Process Improvement Analyst
>- 2000-2007 - Business Intelligence and Supply Chain Planing (modeling, management and operations)

#### :school: Education
>- MS(2010): Agroindustry Production and Management
>- BS(2000): Businesss Administration

#### :mag: Where you find me
>- How to reach me: youtube.com/carvalhoribeiro

<!--
**factorialmap/factorialmap** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

-->

---
output: github_document
---

<pre>

```{r, results='asis', echo=FALSE}
library(htmltools)
library(emoji)
leaf <- function(name, link, desc, space) {
  paste0(
    " ",
    as.character(a(name, href = link)),
    strrep(" ", space),
    "- ",
    desc
  )
}

prismatic <- leaf(
  "prismatic", 
  "https://github.com/EmilHvitfeldt/prismatic", 
  "Simple color manipulation", 
  3
)
smltar <- leaf(
  "smltar",
  "https://smltar.com/",
  "Supervised Machine Learning for Text Analysis in R",
  1
)
emoji <- leaf(
  "emoji",
  "https://emilhvitfeldt.github.io/emoji/",
  "Data and functions about emojis",
  7
)
islr_tidymodels <- leaf(
  "ISLR tidymodels labs",
  "https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html",
  "Tidymodels translation of ISLR labs",
  1
)
r_text_data <- leaf(
  "R-text-data",
  "https://github.com/EmilHvitfeldt/R-text-data",
  "List of textual data in R",
  7
)
r_color_palettes <- leaf(
  "r-color-palettes",
  "https://emilhvitfeldt.github.io/r-color-palettes/",
  "Showcase of all color palettes in R",
  2
)
emilverse <- leaf(
  "emilverse",
  "https://github.com/EmilHvitfeldt/emilverse",
  "Collection of personal packages and templates",
  12
)
blog <- leaf(
  "emilhvitfeldt.com",
  "https://www.emilhvitfeldt.com/",
  "Personal Blog",
  1
)
paletteer <- leaf(
  "paletteer",
  "https://emilhvitfeldt.github.io/paletteer/",
  "Functions for all R color palettes",
  3
)
talks <- leaf(
  "Talks",
  "https://github.com/EmilHvitfeldt/talks",
  "My public talks",
  5
)
xaringan.gallery <- leaf(
  "xaringan.gallery",
  "https://xaringan.gallery/",
  "Collection of examples and custom themes",
  2
)
friends <- leaf(
  "friends",
  "https://emilhvitfeldt.github.io/friends/",
  "Complete script transcription of the Friends",
  5
)
textdata <- leaf(
  "textdata",
  "https://emilhvitfeldt.github.io/textdata/",
  "Download and Load Various Text Datasets",
  4
)
wordsalad <- leaf(
  "wordsalad",
  "https://emilhvitfeldt.github.io/wordsalad/",
  "Extract and Analyze Word Vectors",
  3
)
ggpage <- leaf(
  "ggpage",
  "https://emilhvitfeldt.github.io/ggpage/",
  "Creates Page Layout Visualizations",
  6
)
gganonymize <- leaf(
  "gganonumize",
  "https://github.com/EmilHvitfeldt/gganonymize",
  "Anonymize the labels and text in a ggplot2",
  1
)
textrecipes <- leaf(
  "textrecipes",
  "https://textrecipes.tidymodels.org/",
  "Extra 'Recipes' for Text Processing",
  1
)
themis <- leaf(
  "themis",
  "https://github.com/tidymodels/themis",
  "Extra 'Recipes' steps for unbalanced data",
  6
)
censored <- leaf(
  "censored",
  "https://github.com/tidymodels/censored/",
  "Parsnip wrappers for survival models",
  4
)
workshops <- leaf(
  "Workshops",
  "https://github.com/EmilHvitfeldt/workshops",
  "My Public Workshops",
  1
)
courses <- leaf(
  "Courses",
  "https://github.com/EmilHvitfeldt/courses",
  "My Public Courses",
  3
)
header <- function(emoji, text) {
  res <- glue::glue(":{emoji}: <b>{text}</b>")
  emoji_glue(res)
}

data <- tibble::tribble(
  ~id, ~child, ~text,
  "marcelo", c("videos", "blog", "projects", "books", "other"), header("data", "Marcelo C Anjos"),
  "videos", c("tidymodels", "colors", "text"), header("video", "Videos"),
    "tidymodels", c("textrecipes", "themis", "censored"), header("gear", "tidymodels"),
      "textrecipes", c(), textrecipes,      
  "blog", c("blog"), header("glowing_star", "Blog"),
    "blog", c(), blog,
  "projects", c("smltar"), header("project", "Projects"),
    "smltar", c(), smltar,
  "books", c("pdca", "data_analysis"), header("teacher", "Books"),
    "pdca_book", c(), pdca_book,
    "data_analysis", c(), data_analysis,
  "other", c("congressos"), header("light_bulb", "Congressos"),
    "congressos", c(), talks    
)
cat(paste0(cli::tree(data, width = 10000), collapse = "  \n"))
```

</pre>
