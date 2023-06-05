---
title: "Udacity C++ Course Notes"
description: "My course note about Udentify C++ course"
date: "2022-05-07"
toc: true
badges: true
author: Emre Kara
categories: [Programming, C++, CourseNotes]
image: cpp_logo.png
---

# Udacity - C++ For Programmers: My Course Notes

This article is not a summary of the course, the course content is necessary and perfectly designed and is available on udacity.com, here I have only show some parts of the course content that caught my attention and wanted to quickly remember.

## Introduction

The answers to the following questions in the this section are taken from an interview with Bjarne Stroustrup[^1] (Designer and original implementer of C++) 

### What is C++?

> C++ is a programming language. Its primarily for application that are very demanding on performance, energy consumption and speed.     

<center class="youtube-iframe-wrapper">
    <iframe width="730" height="315" src="https://www.youtube.com/embed/tvDxEgQQK28" frameborder="0" allowfullscreen></iframe>
</center>

### Why learn C++?

> 1. C++ is used in a wide variety of fields.
> 
> 2. It is a language with a lot of features

### What makes C++ different?

> C++ works directly with the hardware and working very efficiently and then having done that it provides really strong abstraction mechanism.

## Basics

# 

1. Constant Enums:
   
   ```cpp
   //define MONTHS as having 12 possible values
   enum MONTHS {Jan, Feb, Mar, Apr,May,Jun,Jul,Aug,Sep,Oct,Nov,Dec};
   
   //define bestMonth as a variable type MONTHS
   MONTHS bestMonth;
   
   //assign bestMonth one of the values of MONTHS
   bestMonth = Jan;
   
   //now we can check the value of bestMonths just like any other variable
   if(bestMonth == Jan)
   {
      cout<<"I'm not so sure January is the best month\n";
   }
   ```

```
out: I'm not so sure January is the best month
```

[^1]: [Bjarne Stroustrup's personel website](https://www.stroustrup.com){:target="https://www.stroustrup.com"}
