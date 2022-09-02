---
permalink: /installation/
title: '<font size=6><center><i class="fas fa-fw fa-chart-area"></i> ACE Scholars R Tutorial Portal</center></font>'
excerpt: "R Tutorials"
toc: true
author_profile: false
redirect_from: 
  - /install
  - /installation.html
  - /installation
---
<center>Installation Guide • <a href="https://zacharycompton.github.io/rtutorials/">R Tutorials</a></center>
<hr>
<br>
<i class="fas fa-fw fa-list"></i> Table of Contents <!--This Table of Contents is Hacked to work, disregard the physical links, it will update off the headers automatically-->
- <a href="https://swirlstats.com/students.html" target="_blank">Learn R, in R</a>
- <a href="https://www.bigbookofr.com/" target="_blank">An Index of R Books</a>
- <a href="https://bookdown.org/ndphillips/YaRrr/" target="_blank">YaRrr, a Pirates Guide to R</a>
{:toc}

<a name="install"></a>
## <i class="fas fa-fw fa-box-open"></i> Installation of R, Rstudio, GIT, and Github
<font size=3>To learn R through ACE Scholar R Tutorials, follow these four key steps on your machine: install R, install R Studio, install GIT, and create a Github account.</font>

1. Installing R

	| Operating System  | Guide	 |
	| --------          | ------ |
	| Windows           | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-r-on-windows-10" target="_blank">Install R</a>   |
	| Mac OSX           | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-r-on-mac-osx" target="_blank">Install R</a>   |
	| Ubuntu            | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-r-on-ubuntu-19.04/18.04/16.04" target="_blank">Install R</a>   |
	
2. Installing Rstudio
	
	| Operating System  | Guide	 |
	| --------          | ------ |
	| Windows           | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-rstudio" target="_blank">Install Rstudio</a>   |
	| Mac OSX           | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-rstudio-and-r-packages" target="_blank">Install Rstudio</a>   |
	| Ubuntu            | <a href="https://www.datacamp.com/tutorial/installing-R-windows-mac-ubuntu#installing-rstudio-and-r-packages" target="_blank">Install Rstudio</a>   |
		
3. Installing GIT

	|All Users			| <a href="https://github.com/git-guides/install-git" target="_blank">Click Here</a>	|
	
4. Create Github Account

	|All Users			| <a href="https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home" target="_blank">Click Here</a>	|
<hr>
<br>
	
<a name="gitname"></a>
## <i class="fa fa-terminal" aria-hidden="true"></i> Introduce Yourself to GIT

![Git Command Line](/images/gitbashex.png)

In the GIT Shell, enter these three commands using your information,
substituting your name and <b>the email associated with your GitHub account.</b>
```
git config --global user.name 'Jane Doe'
git config --global user.email 'jane@example.com'
git config --global --list
```
<hr>
<br>


<a name="hubconnect"></a>
## <i class="fa fa-code-branch" aria-hidden="true"></i> Connect Your RStudio to ACE Tutorial Repository

**Notice!** Linking your RStudio to the ACE-Tutorial repository on Github will ensure the required files (csv, trees, etc) will automatically download into your working directory so that your R code can reference them.  However, if you have issues with your auto connection, we will provide direct links to the files below the video tutorials for manual placement.
{: .notice}
<iframe width="560" height="315" src="https://www.youtube.com/embed/hqRzMsMAKY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
- Alternative Guide to linking to Github: <a href="https://happygitwithr.com/rstudio-git-github.html#clone-the-test-github-repository-to-your-computer-via-rstudio" target="_blank">Click Here</a>
- ACE Tutorials Github URL:	 https://github.com/zacharycompton/ACE-Tutorials.git

<br>
### <i class="fa fa-download" aria-hidden="true"></i> How to manually download a file from Github repository.
<iframe width="560" height="315" src="https://www.youtube.com/embed/ulv6-oTOaII" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<hr>
<br>

<a name="rupdate"></a>
## <i class="fa fa-wrench" aria-hidden="true"></i> Updating your R version through your RGUI

**Notice!** If you are having issues installing or updating packages in RStudio, it is probably because your computer has an outdated version of R.
{: .notice}

- Example of the RGui terminal located in your R folder
![RGui](/images/RGui.png)

- Updating R through the Rgui for Windows/Mac/OSX:  <a href="https://www.linkedin.com/pulse/3-methods-update-r-rstudio-windows-mac-woratana-ngarmtrakulchol" target="_blank">Click Here</a>

- If the above fail, refer to the [Install Section Above](#install) for a fresh install.

<hr>
<br>
		
<a name="rorientation"></a>
## <i class="fas fa-fw fa-video"></i> Recommended Video Orientations

**Notice!** Please keep in mind that a majority of your work will happen in RStudio, and that R and GIT installations are just codebases that support RStudio and Github
{: .notice}

- Quick R Summary: <a href="https://www.youtube.com/watch?v=9kYUGMg_14s&ab_channel=RProgramming101" target="_blank">Why you should use R</a>
- Quick RStudio Summary: <a href="https://www.youtube.com/watch?v=5YmcEYTSN7k&ab_channel=RTutorials" target="_blank">Introduction to RStudio</a>
- Quick Github Summary: <a href="https://www.youtube.com/watch?v=iv8rSLsi1xo&ab_channel=AnsonAlexander" target="_blank">Github Tutorial</a>
<hr>
<br>

<a name="rintro"></a>
## <i class="fas fa-fw fa-code"></i> Beginner R Introductions

**Notice!** These beginner introductions are optional for those that want to get a feel for R before beginning the ACE Tutorials found here: <a href="https://zacharycompton.github.io/rtutorials/">R Tutorials</a>
{: .notice}

- <a href="https://campus.datacamp.com/courses/free-introduction-to-r/chapter-1-intro-to-basics-1?ex=1" target="_blank">Datacamp: Free Intro to R Basics</a>
	- <font size=3>A very quick course on arithmatic, variables, and data types in R</font>
	
- <a href="https://www.codecademy.com/courses/learn-r/lessons/introduction-to-r/exercises/why-r" target="_blank">Codecademy: Free Introduction to R</a>
	- <font size=3>An alternative to Datacamp that offers a similar integrated experience</font>
<hr>
<br>

<a name="rresource"></a>
## <i class="fas fa-fw fa-book"></i> Intermediate R Code Resources

- Swirl: <a href="https://swirlstats.com/students.html" target="_blank">Learn R, in R</a>
	- <font size=3>Learn R from the command console in RStudio</font>
- Big Book of R: <a href="https://www.bigbookofr.com/" target="_blank">An Index of R Books</a>
	- <font size=3>A collection of all the R books you could read in a lifetime</font>
- YaRrr: <a href="https://bookdown.org/ndphillips/YaRrr/" target="_blank">YaRrr, a Pirates Guide to R</a>
	- <font size=3>An index for details on various R subjects</font>
<hr>
<br>
<center>Installation Guide • <a href="https://zacharycompton.github.io/rtutorials/">R Tutorials</a></center>

**Notice!** Please let us know in discord if you find any broken links, outdated info, or errors, Thanks!
{: .notice}