---
date: 2016-05-13T00:00:00+00:00
title: Tutorial 2 - Your first project in 10min
---

This is just an Dummy introduction to demonstrate the use of the "more" tag. Just in case a user clicks on "Tutorials" in the breadcrumb, and then goes to the list of all available tutorials. They will be sorted by date of publication, so do not forget to update it if needed.

And now a bit of lorem ipsum.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dapibus velit id interdum efficitur. Morbi urna risus, consequat at purus ut, ullamcorper interdum diam. Ut fringilla volutpat tincidunt. Cras sit amet nulla lacus. Integer a sem bibendum, euismod turpis sit amet, pharetra dolor:

- Duis dictum id urna eu lobortis
- Integer elementum eget massa in tempus


<!--more-->


# This is where you write your tutorial

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

this should not be visible.
