# Old-Code-Aligning-Images-Horizontally

align chapter-05/aligning-images-horizontally.html HTML
The align attribute was 
commonly used to indicate how 
the other parts of a page should 
flow around an image. It has 
been removed from HTML5 
and new websites should use 
CSS to control the alignment of 
images (as you will see on pages 
411-412). 
I have discussed it here because 
you are likely to come across 
it if you look at older code, and 
because some visual editors still 
insert this attribute when you 
indicate how an image should be 
aligned.
The align attribute can take 
these horizontal values:
left
This aligns the image to the left 
(allowing text to flow around its 
right-hand side).
right
This aligns the image to the right 
(allowing text to flow around its 
left-hand side).


<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" align="left" />There are around 
 10,000 living species of birds that inhabit 
 different ecosystems from the Arctic to the 
 Antarctic. Many species undertake long distance 
 annual migrations, and many more perform shorter 
 irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" 
height="100" align="right" />There are around 
 10,000 living species of birds that inhabit 
 different ecosystems from the Arctic to the 
 Antarctic. Many species undertake long distance 
 annual migrations, and many more perform shorter 
 irregular journeys.</p>
