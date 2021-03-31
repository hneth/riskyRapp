# riskyrApp

<!-- riskyr logo: -->  

<a href = "https://github.com/hneth/riskyr">
<img src = "./www/riskyr_cube_s.png" alt = "riskyr logo" title = "riskyr" width = "160px" align = "right" style = "float:right; border:40; width:160px;"/>
</a>


The **riskyrApp** is an interactive application that complements the R package **riskyr**. 


## Goal

**riskyrApp** is a teaching tool that showcases some functionality of the R package **riskyr**. 
The application is written in [R Shiny](https://shiny.rstudio.com/) and allows using the **riskyr** toolbox without any need for coding.

The main goal of both **riskyr** and **riskyrApp** is to communicate and explain common risk literacy measures in a transparent fashion by providing a set of powerful and interactive representations. 


## Installation

- The current release of **riskyr** is available from [CRAN](https://CRAN.R-project.org/) at <https://CRAN.R-project.org/package=riskyr>: 

```{r}
install.packages("riskyr")  # install riskyr from CRAN client
library("riskyr")           # load the package
```

- The most recent development versions can be installed from their [GitHub](https://github.com) repositories at 
    - R package code: <https://github.com/hneth/riskyr>
    - R Shiny code:   <https://github.com/hneth/riskyrApp/>

```{r}
# install.packages("devtools")
devtools::install_github("hneth/riskyr")
devtools::install_github("hneth/riskyrApp")
```


## About

<!-- uni.kn logo and link to SPDS: -->  

<a href="https://www.spds.uni-konstanz.de/">
<img src = "./www/uniKn_logo_s.png" alt = "spds.uni.kn" align = "right" style = "float: right; border:30;"/>
</a>

**riskyr** originated out of a series of lectures and workshops on risk literacy. 
Its primary designers are 
[Hansjörg Neth](https://www.spds.uni-konstanz.de/hans-neth), 
[Felix Gaisbauer](https://www.spds.uni-konstanz.de/felix-gaisbauer), 
[Nico Gradwohl](https://www.spds.uni-konstanz.de/nico-gradwohl), and 
[Wolfgang Gaissmaier](https://www.spds.uni-konstanz.de/prof-dr-wolfgang-gaissmaier), 
who are researchers at the department of 
[Social Psychology and Decision Sciences](https://www.spds.uni-konstanz.de) at the 
[University of Konstanz](https://www.uni-konstanz.de/en/), Germany. 


### Resources

<!--

The following resources and versions are currently available:

Type:                    | Version:           | URL:                           |        
:------------------------|:-------------------|:-------------------------------|
A. **riskyr** (R package): | [Release version](https://CRAN.R-project.org/package=riskyr) | <https://CRAN.R-project.org/package=riskyr> |
    &nbsp;               | [Development version](https://github.com/hneth/riskyr)       | <https://github.com/hneth/riskyr> | 
B. **riskyrApp** (R Shiny code): | [Online version](http://riskyr.org)                    | <http://riskyr.org> | 
    &nbsp;               | [Development version](https://github.com/hneth/riskyrApp)    | <https://github.com/hneth/riskyrApp> | 
C. Online documentation: | [Release version](https://hneth.github.io/riskyr)            | <https://hneth.github.io/riskyr> | 
    &nbsp;               | [Development version](https://hneth.github.io/riskyr/dev)    | <https://hneth.github.io/riskyr/dev> | 

-->

The following resources and versions are currently available:

<table style="width:100%;">
<colgroup>
<col width="33%" />
<col width="27%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Type:</th>
<th align="left">Version:</th>
<th align="left">URL:</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">A. <strong>riskyr</strong> (R package):</td>
<td align="left"><a href="https://CRAN.R-project.org/package=riskyr">Release version</a></td>
<td align="left"><a href="https://CRAN.R-project.org/package=riskyr" class="uri">https://CRAN.R-project.org/package=riskyr</a></td>
</tr>
<tr class="even">
<td align="left"> </td>
<td align="left"><a href="https://github.com/hneth/riskyr">Development version</a></td>
<td align="left"><a href="https://github.com/hneth/riskyr" class="uri">https://github.com/hneth/riskyr</a></td>
</tr>
<tr class="odd">
<td align="left">B. <strong>riskyrApp</strong> (R Shiny code):</td>
<td align="left"><a href="https://riskyr.org/">Online version</a></td>
<td align="left"><a href="https://riskyr.org/" class="uri">https://riskyr.org</a></td>
</tr>
<tr class="even">
<td align="left"> </td>
<td align="left"><a href="https://github.com/hneth/riskyrApp">Development version</a></td>
<td align="left"><a href="https://github.com/hneth/riskyrApp" class="uri">https://github.com/hneth/riskyrApp</a></td>
</tr>
<tr class="odd">
<td align="left">C. Online documentation:</td>
<td align="left"><a href="https://hneth.github.io/riskyr">Release version</a></td>
<td align="left"><a href="https://hneth.github.io/riskyr" class="uri">https://hneth.github.io/riskyr</a></td>
</tr>
<tr class="even">
<td align="left"> </td>
<td align="left"><a href="https://hneth.github.io/riskyr/dev">Development version</a></td>
<td align="left"><a href="https://hneth.github.io/riskyr/dev" class="uri">https://hneth.github.io/riskyr/dev</a></td>
</tr>
</tbody>
</table>


### Contact

We appreciate your feedback, comments, or questions. 

- Please report any **riskyr**-related issues at <https://github.com/hneth/riskyr/issues>. 

- Email us at <contact.riskyr@gmail.com> if you want to modify or share this software. 


### Reference

<!-- riskyr logo: -->  

<a href = "https://github.com/hneth/riskyr">
<img src = "./www/riskyr_cube_s.png" alt = "riskyr logo" title = "riskyr" width = "160px" align = "right" style = "float:right; border:40; width:160px;"/>
</a>

To cite **riskyr** in derivations and publications use:

-  Neth, H., Gaisbauer, F., Gradwohl, N., & Gaissmaier, W. (2021).    
    riskyr: A toolbox for rendering risk literacy more transparent.    
    Social Psychology and Decision Sciences, University of Konstanz, Germany.    
    Computer software (R package version 0.3.0, Mar. 23, 2021).    
    Retrieved from <https://CRAN.R-project.org/package=riskyr>.   

A BibTeX entry for LaTeX users is: 

    @Manual{riskyr,
      title = {riskyr: A toolbox for rendering risk literacy more transparent},
      author = {Hansjörg Neth and Felix Gaisbauer and Nico Gradwohl and Wolfgang Gaissmaier},
      year = {2021},
      organization = {Social Psychology and Decision Sciences, University of Konstanz},
      address = {Konstanz, Germany},
      note = {R package (version 0.3.0, Mar. 23, 2021)},
      url = {https://CRAN.R-project.org/package=riskyr},
      }    
    
Calling `citation("riskyr")` in the package also displays this information.

<!-- eof. --> 
