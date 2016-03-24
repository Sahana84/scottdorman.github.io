---
layout: post
title: "Book Review: LINQ Quickly"
date: 2008-02-24 19:40:59 -05:00
---

[![LINQ Quickly](http://images.packtpub.com/images/100x123/1847192548.png "LINQ Quickly")](http://www.packtpub.com/#)I was recently introduced to a UK based publisher called [Pact Publishing](http://www.packtpub.com). They are a UK based publisher and have a book focused on the new Language Integrated Query (LINQ) features available in .NET 3.5 called <u>[LINQ Quickly: A practical guide to programming Language Integrated Query with C#](http://www.amazon.com/gp/redirect.html?ie=UTF8&location=http%3A%2F%2Fwww.amazon.com%2Fexec%2Fobidos%2FASIN%2F1847192548%2F&tag=scotdorm-20&linkCode=ur2&camp=1789&creative=9325)</u> by N Satheesh Kumar.

The book provides a good overview of LINQ and it's supporting language features, such as anonymous types, implicit typing, object initializers, extension methods, and expressions. It then builds on that introduction to cover the various LINQ implementations, such as LINQ to Objects, LINQ to XML, and LINQ to SQL. A very thorough look at the different Standard Query Operators closes the book.

Also provided are two simple examples that really help highlight the power and flexibility of LINQ. The first example shows how to create a web site that uses LINQ to populate a data grid and some form elements. The other example shows how to use LINQ against the Outlook object model to retrieve the details of an Outlook contact.

One thing that this book mentions very clearly that hasn't been talked about much is that LINQ to SQL is able to make use of not just embedded SQL but also stored procedures and walks the reader through the steps necessary in order to make effective use of LINQ and stored procedures.

As I mentioned, the last chapter provides a very thorough look at the Standard Query Operators and breaks them up into the different types:
 <table cellspacing="0" cellpadding="2" width="786" border="1"> <tbody> <tr> <td valign="top" width="199">**Operators**</td> <td valign="top" width="585">**Description**</td></tr> <tr> <td valign="top" width="199">Aggregation</td> <td valign="top" width="585">Used to compute a single value from a collection of values.</td></tr> <tr> <td valign="top" width="199">Projection</td> <td valign="top" width="585">Used to transform elements.</td></tr> <tr> <td valign="top" width="199">Concatenation</td> <td valign="top" width="585">Used to concatenate one sequence to another.</td></tr> <tr> <td valign="top" width="199">Element</td> <td valign="top" width="585">Used to return a single element from a sequence of elements.</td></tr> <tr> <td valign="top" width="199">Conversion</td> <td valign="top" width="585">Used to change the type of the input object.</td></tr> <tr> <td valign="top" width="199">Equality</td> <td valign="top" width="585">Used to check for equality of two sequences.</td></tr> <tr> <td valign="top" width="199">Generation</td> <td valign="top" width="585">Used for generating a new sequence of values.</td></tr> <tr> <td valign="top" width="199">Grouping</td> <td valign="top" width="585">Used for grouping elements together that share a common attribute.</td></tr> <tr> <td valign="top" width="199">Join</td> <td valign="top" width="585">Used to associate objects from one data source with objects in another data source based on a common attribute.</td></tr> <tr> <td valign="top" width="199">Partitioning</td> <td valign="top" width="585">Used to divide an input sequence into two or more sections and then return the one section that is required.</td></tr> <tr> <td valign="top" width="199">Quantifiers</td> <td valign="top" width="585">Used to perform the operation of checking whether some or all of the elements in a sequence satisfy a condition.</td></tr> <tr> <td valign="top" width="199">Restriction</td> <td valign="top" width="585">Used to restrict the query result to contain elements that satisfy the specific condition.</td></tr> <tr> <td valign="top" width="199">Set</td> <td valign="top" width="585">Used to get the result sets based on the presence or absence of equivalent elements in the same or another collection.</td></tr> <tr> <td valign="top" width="199">Ordering</td> <td valign="top" width="585">Used for ordering elements in a sequence based on one or more attributes.</td></tr></tbody></table> 

While the style of writing in the book was a little hard to follow, the technical content of the book appeared to be both accurate and thorough, taking the most in-depth look at LINQ to XML and then the Standard Query operators.