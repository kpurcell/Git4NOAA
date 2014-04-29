---
title       : Reproducible Research in Fisheries
subtitle    : Git, Markdown, knitr and Pandoc for scientific workflow
author      : K.M. Purcell
job         : Postdoctoral Associate
logo        : noaa.jpg
framework   : io2012        # {io2012, html5slides, shower, dzslides, deckjs...}
hitheme     : solarized_light  # {tomorrow, solarized_light, web2.0}
widgets     : [mathjax, quiz, bootstrap]    # {mathjax, quiz, bootstrap}
mode        : selfcontained      # {standalone, draft}
license     : by-nc-sa
github      : 
 user       :kpurcell
 repo       :Git4NOAA

--- .segue .nobackground .dark

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

## Objectives

* Introduce Reproducible Research
* 

---

-The reason what we do in fisheries is especially fitted for these approaches is because our work is inherently open in that it is for the public good and open to public criticism
-also indefinately repetitive meaning that reproducibility is not only a necessity but also expedient.

---

## Tools for Reproducible Research

* Version control (Git)
* Markdown
* knitr
* pandoc

---

## Version Control


---

## Version control System (VCS)

1. Version control systems (VCS)
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

![gitIcon](http://thril.uws.edu.au/wp-content/uploads/2013/10/git-icon.png)

---
## Git & GitHub




--- 

## Slide 2

![codeReuse](http://www.phdcomics.com/comics/archive/phd031214s.gif)

## Dynamic Documents

>"Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to humans what we want the computer to do."

>-- Donal E. Knuth, Literate Programming, 1984

## Why?

1. Increased repeatiblity
2. Reduced creation time (image transfer)
3. Reduced transposition errors (no errors in tables)
4. Reduced re-creation time (no repition when data changes)

---

## Sweave Example
```
\section{Exploratory Data Analysis}

\begin{figure}
\begin{center}

<<fig=TRUE,echo=FALSE>>=
sunflowerplot(br.gss.dat$lon, br.gss.dat$lat, main="Sampling Intensity", xlab="Lon",
              ylab="Lat")
map("state",fill=T,col="gray",add=T)
@

\caption{This is a Sunflower plot showing spatial distribution of sampling intensity}
\label{fig:sunflower}
\end{center}
\end{figure}

The spatial distribution for sampling intensity for entire Gulf Shrimp statistics dataset can be seen in the sunflower plot \ref{fig:sunflower}.  Each line is a samples and therefore more developed
petals represent positions with higher sampling.  The sampling intenstiy uniform and plenty dense. 
```

---

## Rmarkdown Example

![dynDocEx](http://www.rstudio.com/images/docs/markdownChunk.png)

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



---

![workFlow](http://i1.wp.com/ouseful.files.wordpress.com/2012/07/rchitecture1.png)

---

## Sources for more information

* Lessions for @scarpentry (http://software-carpentry.org/v4/index.html)

---
## Pandoc conversion utility

![pandoc](http://johnmacfarlane.net/pandoc/diagram.png)

--- &twocol

## Pandoc 

*** =left  

**INPUT**  
  * markdown  
  * HTML  
  * DocBook  
  * LaTex  
  * MediaWiki  

*** =right  

 **OUTPUT**  
  * Word docx  
  * LaTex  
  * LaTex Beamer  
  * PDF  
  * HTML5  

---

## File Tracking (Old way)
![vcs](http://www.phdcomics.com/comics/archive/phd101212s.gif)

---

* with "track changes" ```accepted==gone```
* VCS maintains a full record with provenance (date, author, changes)
 + SSH hashes
 


---
## Branches in Git

![gitBranch](C:\\Users\\Kevin.Purcell\\Documents\\GitHub\\Git4NOAA\\git4NOAA\\images\\gitBranch.png)


---

source code management
