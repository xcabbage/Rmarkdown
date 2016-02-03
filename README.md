# Rmarkdown

http://54.93.94.196/auth-sign-in

Kaposztassy_Gabor@student.ceu.edu

**BOLD** and *italics*

---
* a
* b
* c
---

```{r,echo=FALSE}
library(pander)
lm(mpg ~ wt, data=mtcars)
summary(lm(mpg ~ wt, data=mtcars))

pander(summary(lm(mpg ~ wt, data=mtcars)))
pander(lm(mpg ~ wt, data=mtcars), caption = 'foobar')

```
