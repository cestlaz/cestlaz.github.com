---
published: true
layout: post
name: Databases - the next day
title: Databases - the next day
tags: 
---

Two days ago I asked the students, in small groups, to come up with a design to store a school (or school district) database.

Yesterday we discussed the designs.

All the students took our brand of AP Computer Science last year - a
superset of the old AB curriculum and in that class they implemented a
number of data structures such as binary search trees and hash tables,
but they really didn't have an opportunity to design something more
comprehensive.

At the start, suggestions were based around simple monolithic
designs. A class to represent a student, an array or hash table of
these classes and in each object, an array of grades or something like
that. 

Soon the discussion turned to optimizing search based on different
"keys." Searching by student id or searching by name. This led to the
idea of indices. For example, sorting an array of name keys that point
into our main database.

This was followed by less monolithic ideas -- essentially ideas behind
linking different tables using key fields. For example, a student
table with student id and a transcript table where each line has a
student id, a class, grade, teacher, and date.

