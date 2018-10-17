---
title: Spreadsheets Lesson 6
layout: post
author: mark.calderan
permalink: /spreadsheets-lesson-6/
source-id: 1DWVmcvazfgU3W7jfoNQzENXpPED0QYp4kfFMDH9k2gw
published: true
---
<table>
  <tr>
    <td>Title</td>
    <td>Lesson 6 Spreadsheets</td>
    <td>Lesson Date</td>
    <td>11/10/18</td>
  </tr>
</table>


<table>
  <tr>
    <td>Lesson Review</td>
  </tr>
  <tr>
    <td>This lesson the class was all about making the caesar cypher program look better and be more practical. The functions we were using were left right and mid, to get the user to type in one cell and the functions separating the letters out into separate cells so that they could be processed. 

The problem with this is that there is no deconcatenate, or unconcatenate function, so Mr Tansley's method was to use left right and mid to give each cell a number and referencing that number to put the letter in a different cell.

However Robert found a much more direct method which does not involve writing a long string of numbers out to start referencing other cells. this method uses the REGEXEXTRACT function which is formulated like this in my spreadsheet.
=REGEXEXTRACT(C2,REPT("(.)",len(C2)))
 so, C2 is the cell that the message is in, and the REGEXEXTRACT function will take the message in the cell C2 and extract each letter/ symbol and separate them into their own individual cells. however this only works with letters.

I think that this is easier to use once you understand it, (which to be honest I don't completely) but Mr Tansley's is easier to get the hang of, as it is more logical and mathematical. Once I had implemented Robert's code and attempt to understand it for about 5 minutes, I went around asking other people if they needed my help on putting the essentially deconcatenate function in. the only problem being I did not know the method that Mr Tansley was using properly. This meant that I was being useless for a chunk of the lesson. I then realised this and tryed to use ASKII character to do my biary cypher again, which again, didn't go very well.</td>
  </tr>
</table>


