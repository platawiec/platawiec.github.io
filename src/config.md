<!-----------------------------------------------------
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
------------------------------------------------------->
@def website_title = "Pawel's Homepage"
@def website_descr = "Technical posts"
@def website_url   = "https://platawiec.github.io/"

@def author = "Pawel Latawiec"

<!-----------------------------------------------------
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
------------------------------------------------------->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}


<!-- Put a box around something and pass some css styling to the box
(useful for images for instance) e.g.:
\style{width:80%;}{![](path/to/img.png)} -->
\newcommand{\style}[2]{~~~<div style="!#1;margin-left:auto;margin-right:auto;">~~~!#2~~~</div>~~~}
