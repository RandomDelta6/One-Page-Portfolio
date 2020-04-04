---
layout: post
title:  "Initial Blog Post"
date:   2020-04-02 09:19:47 +0530
categories: blog new
permalink: /blog/new/
author: Rishav
---

<img src="/assets/img/header.jpg" />

This is a demo blog to illustrate my CV.
This was created on 4 April, 2020 using Ruby Gems and Jekyll.

A little bit about me.  
I am a first year student at Kalyani Goverenment Engineering College and currently an intern for the Developer's Club.  
My hobbies include drawing/sketching, Reading story books,tinkering with gadgets, disassembling them and trying to put them back together , apply various modifications to it, watching movies and gardening.  
I am really enthusiastic about learning new skills and working with people on shared projects.  

{%- for state in page.states -%}
  {{ state.capital }}
{%- endfor -%}


