
This is a placeholder repo to sketch out a web app that can be used to help write letters to legislature.

The requirements that separate it from normal document-writing features are:

* Sometimes you want to write multiple letters about the same topic but personalized. So using templates isn't enough; a living document is a template. It is personalized in child documents, but changes to some parts of child documents should not be reflected in the parent document.  Changes to parts that are not specific to child documents should be reflected in the parent document.  The app should detect where the changes are being made and which other documents they should percolate to.

* Integration with the current list of legslatures and bills being considered in the chambers.

* Not necessarily multi-user with the latest in collaboration features, but that could be a great feature set for v2.

For instance, I'm writing a letter to a sponsor of a bill who is in VA.  I also want to write to my local legislature to ask about supporting of the bill (for upcoming votes) and to mention that I've written to the bill's sponsors.  Having the boilerplate about my support in the latter documents update if I make changes in the first letter, while maintaing the personalized message indicating I've written to the bill's sponsors, would make managing changes much much easier, while enabling a consistently stated message in all letter for one topic.

Sep 6th, 201:

Some more thinkng on this.  It should supports a couple different UI's: One should b tild and the other a more traditionel MultiWindow document managemtn layout.

In the tiled arragnment, you would have the screen divides into, for exampl, howevery many congresspeopl are being written to.  If the letters were being writen to, say, 4 differnt people, then the screen would have 4 quadrants eqch contankng the letter specific to that congresserson.

In the traditional MultiWinnow arrangemetn, the window for each letter would be hidden behind each ohter and resziable like application in a traditonal UI.

Also, a very ncie faeture to have would be to be able to semanticaly understand the "chunks" of the letters and know which letter each chunk beloned to.  In a UI that displayd a list of chunk, you could click on each cunk to only work on leters that contained thay chunk.
