# Document Object Model Tree 

The tree-representation of a Document Object Model. This project was created for CS 112 (Data Structure, Spring 2015) at Rutgers University. The full assignment specification can be found here: http://www.cs.rutgers.edu/courses/112/classes/spring_2015_venugopal/progs/prog3/prog3.html

The Document Object Model (DOM) is an interface that represents the HTML layout of a document. It allows other scripts and programs to modify this structure, which can then be pushed back to the webpage. 

The following HTML code:
   <html>
   <body>
   <center>The <em>quick</em> brown fox</center>
   </body>
   </html>

Would be shown in a browser window as follows:

   The quick brown fox

And the tree representation would be:
 
   html
          |
         body
          |
        center
          |
    --------------
    |     |      |     
  The    em      brown fox
          |     
        quick   
