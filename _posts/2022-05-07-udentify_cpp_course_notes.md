---
toc: true
layout: post
description: My course note about Udentify C++ course
categories: [markdown]
comments: true
author: Emre Kara
categories: [Programming, C++, CourseNotes]
title: Udentify C++ For Programmers Course - My Course Notes
image: images/cpp_logo.png
---

# Udentify - C++ For Programmers: My Course Notes

bu yazı kesinlikle kursun bir özeti değildir, kurs içeriği gerekli ve mükkemmel düzayn edilmiş ve udacity.com'da yer almaktadır, burada sadece kurs içeriğinden dikkatimi çeken ve hızlıca hatırlamak istediğim bazı kısımlara yer verdim.

## Introduction

The answers to the following questions in the this section are taken from an interview with Bjarne Stroustrup[^1] (Designer and original implementer of C++) 

### What is C++?

> C++ is a programming language. Its primarily for application that are very demanding on performance, energy consumption and speed.     

> youtube: https://youtu.be/tvDxEgQQK28

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

[![Test Video](https://img.youtube.com/vi/tvDxEgQQK28/0.jpg)](https://www.youtube.com/watch?v=tvDxEgQQK28)

{% include youtube.html text="https://youtu.be/tvDxEgQQK28" %}

{% include youtube.html base_url="https://youtu.be/tvDxEgQQK28" %}

{% include alert.html text="You can include alert boxes" %}

{% include info.html text="You can include info boxes" %}

{% include important.html text="You can include important boxes" %}

{% include note.html text="You can include note boxes" %}

{% include tip.html text="You can include tip boxes" %}

{% include warning.html text="You can include warning boxes" %}

<img title="" src="https://raw.githubusercontent.com/emrekaragh/blog/master/images/logo.png" alt="" data-align="center" width="368">

[^1]: [Bjarne Stroustrup's personel website](https://www.stroustrup.com){:target="_blank"}
