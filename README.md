# Omics data analysis (WSBIM2122)

- Course material: https://uclouvain-cbio.github.io/WSBIM2122/

# Fork of WSBIM2122: Introduction to Reproducible Research in Bioinformatics

This is a **fork** of the original [WSBIM2122](https://uclouvain-cbio.github.io/WSBIM2122/) course materials developed by the Computational Biology and Bioinformatics (CBIO) group at UCLouvain.

The purpose of this fork is to [briefly explain your intent — e.g., adapt it for personal learning, translate it, modify for a local course, etc.]

## Original Authors

The original content was created by:

- Laurent Gatto
- Axelle Loriot
- Other contributors, as listed in the original repository

You can find the original source code and materials here:  
👉 [Original GitHub Repository](https://github.com/UCLouvain-CBIO/WSBIM2122)

## License

This work is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license.

I you wish to build this book locally, you'll need
[bookdown](https://bookdown.org/yihui/bookdown/) and a fork of
[msmbstyle](https://github.com/lgatto/msmbstyle).

```{r combilebook1, eval=FALSE}
install.packages("bookdown")
devtools::install_github("lgatto/msmbstyle")
```

In the course's work directory, simply type

```{r combilebook2, eval=FALSE}
bookdown::render_book(".")
```
