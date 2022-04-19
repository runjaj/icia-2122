+++
author = "Javier Arántegui"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

prepath = "icia-2122"

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = false
website_title = "Control de Procesos 21-22"
website_descr = "Apuntes de Control de Procesos 21-22"
website_url   = "https://runjaj.github.io/icia-2122/"


+++

\newcommand{\figenv}[3]{
~~~
<figure style="text-align:center;">
<img src="!#2" style="padding:0;#3" alt="#1"/>
<figcaption>#1</figcaption>
</figure>
~~~
}

\newcommand{\note}[1]{@@note @@title ⚠ Note@@ @@content #1 @@ @@}

\newcommand{\warn}[1]{@@warning @@title ⚠ Warning!@@ @@content #1 @@ @@}

\newcommand{\tip}[1]{@@tip @@title ⚠ Tip@@ @@content #1 @@ @@}