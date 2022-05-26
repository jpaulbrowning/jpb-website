---
title: Resume | Jason Browning
date: 2022-05-26
permalink: /resume/index.html
eleventyNavigation:
  order: 20
  key: Resume 
---
Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@jpaulbrowning 
mszep
/
pandoc_resume
Public
Code
Issues
23
Pull requests
3
Actions
Projects
Wiki
Security
Insights
pandoc_resume/styles/chmduquesne.css
@chongchonghe
chongchonghe Some minor modification to styles/chmduquesne.css to improve the appe…
…
Latest commit 6f650a3 on Jan 26, 2020
 History
 1 contributor
95 lines (87 sloc)  1.75 KB
   
<style type="text/css">
/*
 * Copyright 2013 Christophe-Marie Duquesne <chmd@chmd.fr>
 *
 * CSS for making a resume with pandoc. Inspired by moderncv.
 *
 * This CSS document is delivered to you under the CC BY-SA 3.0 License.
 * https://creativecommons.org/licenses/by-sa/3.0/deed.en_US
 */

/* Whole document */
body {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    max-width: 800px;
    margin: auto;
    background: #FFFFFF;
    padding: 10px 10px 10px 10px;
}

/* Title of the resume */
h1 {
    font-size: 55px;
    color: #757575;
    text-align:center;
    margin-bottom:15px;
}
/* h1:hover { */
/*     background-color: #757575; */
/*     color: #FFFFFF; */
/*     text-shadow: 1px 1px 1px #333; */
/* } */

/* Titles of categories */
h2 {
    /* This is called "sectioncolor" in the ConTeXt stylesheet. */
    color: #397249;
}
/* There is a bar just before each category */
h2:before {
    content: "";
    display: inline-block;
    margin-right:1%;
    width: 16%;
    height: 10px;
    /* This is called "rulecolor" in the ConTeXt stylesheet. */
    background-color: #9CB770;
}
/* h2:hover { */
/*     background-color: #397249; */
/*     color: #FFFFFF; */
/*     text-shadow: 1px 1px 1px #333; */
/* } */

/* Definitions */
dt {
    float: left;
    clear: left;
    width: 17%;
    font-weight: bold;
}
dd {
    margin-left: 17%;
    margin-bottom:7px;
}
p {
    margin-top:0;
    margin-bottom:7px;
}

/* Blockquotes */
blockquote {
    text-align: center
}

/* Links */
a {
    text-decoration: none;
    color: #397249;
}
a:hover, a:active {
    background-color: #397249;
    color: #FFFFFF;
    text-decoration: none;
    text-shadow: 1px 1px 1px #333;
}

/* Horizontal separators */
hr {
    color: #A6A6A6;
}

table {
    width: 100%;
}
</style>


Johnny Coder
============

-------------------     ----------------------------
1 MyAddress                        email@example.com
MyTown 1000                          @twitter_handle
MyCountry                           1800 my-phone-nr
-------------------     ----------------------------

Education
---------

2010-2014 (expected)
:   **PhD, Computer Science**; Awesome University (MyTown)

    *Thesis title: Deep Learning Approaches to the Self-Awesomeness
     Estimation Problem*

2007-2010
:   **BSc, Computer Science and Electrical Engineering**; University of
    HomeTown (HomeTown)

    *Minor: Awesomeology*

Experience
----------

**Your Most Recent Work Experience:**

Short text containing the type of work done, results obtained,
lessons learned and other remarks. Can also include lists and
links:

* First item

* Item with [link](http://www.example.com). Links will work both in
  the html and pdf versions.

**That Other Job You Had**

Also with a short description.

Technical Experience
--------------------

My Cool Side Project
:   For items which don't have a clear time ordering, a definition
    list can be used to have named items.

    * These items can also contain lists, but you need to mind the
      indentation levels in the markdown source.
    * Second item.

Open Source
:   List open source contributions here, perhaps placing emphasis on
    the project names, for example the **Linux Kernel**, where you
    implemented multithreading over a long weekend, or **node.js**
    (with [link](http://nodejs.org)) which was actually totally
    your idea...

Programming Languages
:   **first-lang:** Here, we have an itemization, where we only want
    to add descriptions to the first few items, but still want to
    mention some others together at the end. A format that works well
    here is a description list where the first few items have their
    first word emphasized, and the last item contains the final few
    emphasized terms. Notice the reasonably nice page break in the pdf
    version, which wouldn't happen if we generated the pdf via html.

:   **second-lang:** Description of your experience with second-lang,
    perhaps again including a [link] [ref], this time placing the url
    reference elsewhere in the document to reduce clutter (see source
    file). 

:   **obscure-but-impressive-lang:** We both know this one's pushing
    it.

:   Basic knowledge of **C**, **x86 assembly**, **forth**, **Common Lisp**

[ref]: https://github.com/githubuser/superlongprojectname

Extra Section, Call it Whatever You Want
----------------------------------------

* Human Languages:

     * English (native speaker)
     * ???
     * This is what a nested list looks like.

* Random tidbit

* Other sort of impressive-sounding thing you did
view raw