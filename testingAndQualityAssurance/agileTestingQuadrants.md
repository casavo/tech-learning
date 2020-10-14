# Agile Testing Quadrants

**Status: draft**

Agile Testing Quadrants are a tool that should help team to plan 
their testing (activities).

The original idea comes from this [Brian Marick post][brian-marik-post], 
subsequently revisited and re-proposed by several people with little 
changes in wording

Quandrants are deeply described in [Agile Testing][book-agile-testing] and
[More Agile Testing][book-more-agile-testing] books from Crispin/Gregory.

## How Quandrants Works

Long story short: "testing" activities should help team to collect info about 
"doneness" of a working unit (for instance an user story), quadrants helps to
understand which testing activity is more suited to:
* guide and confirm the implementation of business value
* guide and confirm the implementation of actual code
* critique and discover the product from a business value point of view
* critique and discover the product from a technology implementation point of view

Here is the latest ([2019][book-agile-testing-condensed]) version from Crispin/Gregory

![alt text][agile-testing-quadrants-latest]

Example: we are working on an user story that involves create and add a brand
new breadcrumb element in some web pages, aiming to help end users to better 
navigate the website (and reduce bounce, increase visit time, and so on)

Quadrants may help us to understand that we:
* could need some "e2e" automated test to confirm the element is present 
  in page, can be clicked, and points to desired pages inside actual website
* could need some "unit" or "component" test to confirm internal code used 
  to build a generic breadcrumb doesn't fail on corner case
* could need some "usability" test to discover if end users will understand 
  how it works
* could need some "performace" test to discover if we'll increase database 
  response time due new extra info to collect in order to build the breadcrumb

You can also flip the point of view and use the quadrants to understand if a 
testing activity is worth. For example, you can ask yourself: as developer,
am I using unit tests to understand what the code needs to do? or component 
tests to consolidate design of a deployable part of the system? 

## Quick References

* [Lisa Crispin Slides (2009)][slides-crisping-quadrants-2009]
* [James Back critique to Crispin/Gregory version][slides-back-quadrants]  
* [Gojko Adzic's take on quadrants][post-adzic-quadrants]
* [Quick 'n' Dirty slides for internal intro to testing quadrants][intro-to-mind-tools-for-testing]



[brian-marik-post]: http://www.exampler.com/old-blog/2003/08/22/#agile-testing-project-2
[book-agile-testing]: https://www.goodreads.com/book/show/5341009-agile-testing
[book-more-agile-testing]: https://www.goodreads.com/book/show/22253245-more-agile-testing
[book-agile-testing-condensed]: https://www.goodreads.com/book/show/48516589-agile-testing-condensed
[agile-testing-quadrants-latest]: ./agile-testing-quadrants-latest.png "Latest from Crispin/Gregory"
[intro-to-mind-tools-for-testing]: https://docs.google.com/presentation/d/1oiK4fm_BLJsSPocQr8C85CSS07CZE1SBkSOHVfs_kpc/edit?usp=sharing
[slides-crisping-quadrants-2009]: https://lisacrispin.com/downloads/AdpTestPlanning.pdf
[slides-back-quadrants]: https://www.slideshare.net/HcmcStc/the-new-agile-testing-quadrants-bringing-skilled-testers-and-developers-together-james-bach
[post-adzic-quadrants]: https://gojko.net/2013/10/21/lets-break-the-agile-testing-quadrants/