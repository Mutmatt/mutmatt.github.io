---
id: 29
title: Struts2 Field Conversion Auto Validation
date: 2012-10-10T20:56:47+00:00
layout: post
permalink: /struts2-field-conversion-auto-validation/
tags:
  - development
  - web
  - auto-validation
  - invalid.fieldvalue
  - struts
---
Struts 2, a pull a rabbit out of your hat type magical technology, is used in many web app tech stacks. 

![struts rabbit](http://i0.wp.com/www.wpclipart.com/working/people_at_work/magician_rabbit_hat.png) 
-----
I found a very interesting tid bit in this technology that I failed to find a direct answer to on the infamous interwebs: `Invalid Field Value for Field "XXXXXXXX"` This error is auto generated by struts when a data conversion error occurs such as String -> Date. Not to fear! This error can be customized EASILY if you are using message property files! Just add one line: `invalid.fieldvalue.XXXXXX` (where `XXXXXX` is the field name)!

Post one done! 

~ME
