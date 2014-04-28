---
title       : Reproducible Research in Fisheries
subtitle    : applications of Git, Markdown, knitr and Pandoc for scientific workflow
author      : K.M. Purcell
job         : Postdoctoral Associate
framework   : io2012        # {io2012, html5slides, shower, dzslides, deckjs...}
hitheme     :               # {tomorrow, solarized_light, web2.0}
widgets     : [mathjax, quiz, bootstrap]    # {mathjax, quiz, bootstrap}
mode        : selfcontained      # {standalone, draft}
license     : by-nc-sa
github      : 
 user       :kpurcell
 repo       :Git4NOAA

---

<!-- Limit image width and height -->
<style type='text/css'>
img {
    max-height: 560px;
    max-width: 964px;
}
</style>

<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>


---
## Slide 1

* Reproducible Research
-The reason what we do in fisheries is especially fitted for these approaches is because our work is inherently open in that it is for the public good and open to public criticism
-also indefinately repetitive meaning that reproducibility is not only a necessity but also expedient.
* Open Science
* Scientific Workflow

---

## Dynamic Documents

>"Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to humans what we want the computer to do."

>-- Donal E. Knuth, Literate Programming, 1984

---

## Tools for Reproducible Research

* Version control (Git)
* Markdown
* knitr
* pandoc

---

## Version Control

---

## Markdown
* John Mc??
* Simplicity over $\LaTeX$

---

## Slide 2

* Literate Programming (Donald Knuth)
* Clear provenance
* Repeatibility
* Collaboration
* Markdown
* Version Control

---

## Testing the command line
* testing 

---

## Knitr vs Sweave 
* the maturation of literate

---

## Version control System (VCS)

1. Version control systems (VCS)
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

![gitIcon](http://thril.uws.edu.au/wp-content/uploads/2013/10/git-icon.png)

---
## Git & GitHub




--- .class #id 

## Slide 2

![codeReuse](http://www.phdcomics.com/comics/archive/phd031214s.gif)

---

![workFlow](http://i1.wp.com/ouseful.files.wordpress.com/2012/07/rchitecture1.png)

---

## Sources for more information

* Lessions for @scarpentry (http://software-carpentry.org/v4/index.html)

---
## Pandoc conversion utility

![pandoc](http://johnmacfarlane.net/pandoc/diagram.png)

--- &twocol w1:50% w2:50%

## Pandoc 
Swiss army knife for docs

*** left

  * markdown
  * reStructureText
  * textile
  * HTML
  * DocBook
  * LaTex
  * MediaWiki
  * OPML
  * Haddock

*** right

  * Word docx
  * ODT
  * LaTex
  * LaTex Beamer
  * PDF
  * XHTML
  * HTML5
  * HTML5 Slides
  * reveal.js
  * Slideous
  * S5
  * DZSlides

---

## File Tracking (Old way)
![vcs](http://www.phdcomics.com/comics/archive/phd101212s.gif)

---

* with "track changes" ```accepted==gone```
* VCS maintains a full record with provenance (date, author, changes)
 + SSH hashes
 


---
## Branches in Git

![gitBranch](C:\\Users\\Kevin.Purcell\\Documents\\GitHub\\Git4NOAA\\git4NOAA\\gitBranch.png)


---

source code management
