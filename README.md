<div align="center">

# Algorithms, Part II
by Princeton University

[![school-badge]][school]
[![license-badge]][&copy]

</div>

<br>

## Course Description:
This course covers the essential information that every serious programmer needs to know about algorithms and data structures, with emphasis on applications and scientific performance analysis of Java implementations. Part I covers elementary data structures, sorting, and searching algorithms. Part II focuses on graph- and string-processing algorithms.

All the features of this course are available for free.  It does not offer a certificate upon completion.

<br>

| Project                | Goals                                                                                                                                                                                                                                                                                                                                                                                                         |                               |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :---------------------------- |
| [WordNet]              | Build the WordNet digraph: each vertex <i>v</i> is an integer that represents a synset, and each directed edge <i>v→w</i> represents that <i>w</i> is a hypernym of <i>v</i>. The WordNet digraph is a <i>rooted DAG</i>: it is acyclic and has one vertex—the <i>root</i>—that is an ancestor of every other vertex. However, it is not necessarily a tree because a synset can have more than one hypernym. | [view specifications][spec01] |
| [Seam Carving]         | Create a data type that resizes a <i>W</i>-by-<i>H</i> image using the seam-carving technique.                                                                                                                                                                                                                                                                                                                | [view specifictaions][spec02] |
| [Baseball Elimination] | Given the standings in a sports division at some point during the season, determine which teams have been mathematically eliminated from winning their division.                                                                                                                                                                                                                                              | [view specifications][spec03] |
| [Boggle]               | Write a program to play the word game Boggle®.                                                                                                                                                                                                                                                                                                                                                                | [view specifications][spec04] |
| [Burrows-Wheeler]      | Implement the <i>Burrows–Wheeler data compression algorithm</i>. This revolutionary algorithm outcompresses <i>gzip</i> and <i>PKZIP</i>, is relatively easy to implement, and is not protected by any patents. It forms the basis of the Unix compression utility <i>bzip2</i>.                                                                                                                              | [view specifications][spec05] |

<br>

---
By viewing and/or interacting with these files as a current or future student of computer science, computer electronics, computer information systems, or related field of study, you agree to the terms of the [Academic Honesty Policy].

<!-- quick links -->
<!-- badge info -->
[school-badge]:https://img.shields.io/badge/Coursera-Algorithms%202-ffffff?logo=coursera&labelColor=0056D2&style=for-the-badge
[school]:https://www.coursera.org/learn/algorithms-part2 "view course"
[license-badge]:https://img.shields.io/github/license/parasiticfrisk/algorithms-part-2?color=informational&style=for-the-badge
[&copy]:LICENSE "MIT License"
<!-- assignments -->
[WordNet]:assignment/wordnet
[Seam Carving]:assignment/seam
[Baseball Elimination]:assignment/baseball
[Boggle]:assignment/boggle
[Burrows-Wheeler]:assignment/burrows
<!-- specifications -->
[spec01]:https://coursera.cs.princeton.edu/algs4/assignments/wordnet/specification.php
[spec02]:https://coursera.cs.princeton.edu/algs4/assignments/seam/specification.php
[spec03]:https://coursera.cs.princeton.edu/algs4/assignments/baseball/specification.php
[spec04]:https://coursera.cs.princeton.edu/algs4/assignments/boggle/specification.php
[spec05]:https://coursera.cs.princeton.edu/algs4/assignments/burrows/specification.php
[Academic Honesty Policy]:academic_honesty_policy
