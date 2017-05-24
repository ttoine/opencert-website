---
date: 2016-06-13T00:00:00+00:00
title: Tutorial 1 - Install and run
---

## This is where you write your tutorial

You can put screenshots, graphics and other picture in "/static/images/tutorials/" and insert them like this:

<img src="../../images/tutorials/graphic.jpg" class="img-responsive">

And of course, you can add some code. Below is an example.

				/* CallingMethodsInSameClass.java
				 *
				 * illustrates how to call static methods a class
				 * from a method in the same class
				 */

				public class CallingMethodsInSameClass
				{
					public static void main(String[] args) {
						printOne();
						printOne();
						printTwo();
					}

					public static void printOne() {
						System.out.println("Hello World");
					}

					public static void printTwo() {
						printOne();
						printOne();
					}
				}

Et voilà, you have all the basics you need.

<!--more-->

Before the "more" tag, this is the resume of the tutorial, or the introduction. This is usefull when a user see the list of all the available tutorials, via the breadcrumb.

So, after the "more" tag, this is where you put the complete tutorial.
