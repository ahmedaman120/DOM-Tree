# Document Object Model Tree 

The tree-representation of a Document Object Model. This project was created for CS 112 (Data Structure, Spring 2015) at Rutgers University. The full assignment specification can be found here: http://www.cs.rutgers.edu/courses/112/classes/spring_2015_venugopal/progs/prog3/prog3.html

The Document Object Model (DOM) is an interface that represents the HTML layout of a document. It allows other scripts and programs to modify this structure, which can then be pushed back to the webpage.

The following HTML code:

      <html>
      <body>
      <center>The <em>quick</em> brown fox</center>
      </body>
      </html>

would appear as the following in the webpage:

<html>
<body>
<center>The <em>quick</em> brown fox</center>
</body>
</html>

and the Tree Structure would be:

INSERT TREE STRUCTURE HERE


Once the tree is built, the following methods are implemented upon the tree:

       build(): Builds tree from input HTML file. 
             This method was implemented both recurisevly and iteratively (using a Stack)
             
       replaceTag(): Replaces all occurrences of one tag with another. Only sensible replacements are accepted
       removeTag(): Deletes all occurrences of a tag
             Category 1 (p, em, and b tags): Tag is deleted from tree, with the child moving up one level
             
             Category 2 (ol or ul tags): Tag is deleted from tree. All <li> tags are removed and converted to p tags
       boldRow(): Boldfaces a given row of a table. Every column must have <b> tag attached (single tag does not suffice)
       addTag(): Add tag around all instances of a taggable word
       

The project was completed on March 23rd 2015

