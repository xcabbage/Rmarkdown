# Rmarkdown

http://54.93.94.196/auth-sign-in

Kaposztassy_Gabor@student.ceu.edu

**BOLD** and *italics*

---

necessary new row!!!!
* a
* b
* c

---

---

* 1. change
* 2. commit in R and comment
* 3. push to git
Hhlkhlkhl

---

```{r,echo=FALSE}
library(pander)
lm(mpg ~ wt, data=mtcars)
summary(lm(mpg ~ wt, data=mtcars))

pander(summary(lm(mpg ~ wt, data=mtcars)))
pander(lm(mpg ~ wt, data=mtcars), caption = 'foobar')

```
