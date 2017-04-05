---
layout: page
title: "Instructor Notes"
permalink: /guide/
---

## Instructor notes

### Lesson purpose

Not to teach *data analysis in spreadsheets*
rather teach good
* data organization 
* data cleaning and 
* quality control 
in a spreadsheet program.

### Narrative

#### [Introduction](/00-intro/) 15 min

* teaching data organization in spreadsheets because most people use spreadsheets for
  * data entry or 
  * have data in spreadsheets.
* good practice in data organization is the foundation of their research practice. 
  * Without organized clean data, difficult to apply the things we're teaching in workshop to their data.
  * Much of life as researcher spent on 'data wrangling' stage
  * some can be prevented with good strategies for data collection up front.
* not teaching data analysis or plotting in spreadsheets
  * very manual and not reproducible. 
  * why we're teaching Python!
* spreadsheets - any program like Excel, LibreOffice, OpenOffice.
  * things accidentally done in spreadsheets? pain points!?
  * As people answer highlight some of these issues with spreadsheets

#### [Formatting data](/01-format-data/) 15 min
* Computers
  * very powerful
  * also very literal - do exactly what you tell them to do, so be careful
  * don't understand context, notes in the margin, color-coding, spatial relationships btw data
  * must explain what these things mean, or set data up so that it makes sense to computer
* Good data organization is foundation of every research project
  * very important to create well-formatted tables at start of project
  * before entering data from first experiment
  * lots of choices, but some choices will limit what ability to work in programs like SAS, R, Python
  * be best friend to your future self
  
* Keep track of your steps and keep raw data raw
  * to reproduce analysis later OR
  * do a different analysis later
  * create a new file or tab with cleaned or analyzed data - do not modify original
  * keep track of each step in clean up or analysis in new tab or text document
  * Example: show figure 1
* Variables in columns, observations in rows, data values in cells 
* Cells have only one piece of info - not mix of numbers & text 
  * Example: show figure 2 & 3
* Leave raw data raw - don't touch it
* Export cleaned data to text format like CSV format
  * anyone can use the data
  * required by most data repositories
* Exercise: messy data file - pair up and work together to clean up the data.
*15 minutes*
* Ask for what people did to clean the data.

#### [Common formatting problems](/02-common-mistakes/)

* **Don't go through this episode** except in reference to previous exercise.

#### [Dates as data](/03-dates-as-data/)

* Do the exercise and make the point about dates.

#### [Quality control](/04-quality-control/)
*This lesson is optional*

The challenge with this lesson is that the instructor's version of the spreadsheet software is going to look different than about half the room's. It makes
it challenging to show where you can find menu options and navigate through.

Instead discuss the concepts of quality control, and how things like sorting can help you find outliers in your data.

#### [Exporting data](/05-exporting-data/)

* Have the students export their cleaned data as csv. Reiterate again the need for
data in this format for the other tools we'll be using.


#### Concluding points

* Now your data is organized so that a computer can read and understand it. This
let's you use the full power of the computer for your analyses as we'll see in the
rest of the workshop. 
* While your data is now neatly organized, it still might have errors or missing data
or other problems. It's like you put all your data in the right drawers, but the
drawers might still be messy. The next lesson is going to teach you OpenRefine which 
is great for data cleaning and for some of the quality control that we touched on 
in this lesson. It also has the advantage that it automatically keeps track of the
steps you take. 

### Potential issues

#### Excel looks and acts different on different OSes

The main challenge with this lesson is that Excel looks very different and how you
do things is even different between Mac and PC, and between different versions of
Excel. So, the presenter's environment will only be the same as some of the learners. 

We need better notes and screenshots of how things work on both Mac and PC. But we
likely won't be able to cover all the different versions of Excel. 

If you have a helper who has experience with the other OS than you, it would be good
to prep them to help with this lesson and tell how people to do things in the other OS.

#### People are not interactive or responsive on the Exercise

This lesson depends on people working on the exercise and responding with things
that are fixed. If your audience is reluctant to participate, start out with
some things on your own, or ask a helper for their answers. This generally gets
even a reluctant audience started. 
