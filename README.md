# Introduction
This a a website that allows the user to view movie trailers of some of the All Time Hits in Animated Movies.

# Prerequisites
In order to be able to view the website and run the code one needs to have Python installed on their machines. Use this link for guidelines on how to install Python on your machines.

# Steps to view the code
1. Clone a copy of the "media.py", "entertainment_centre.py" and "fresh_tomatoes.py" files on your system
2. To view the code one may use the Python IDLE or any other Editor

# Overview of the code:
1. The file "media.py" has defined a data structure, where Movie is a class defining the parameters as required for each movie.
2. The file "entertainment_centre.py" has multiple instances of that Python Class to represent the favorite movies; grouped all the instances together in a list, and then passed this list to a function open_movies_page() which is defined in "fresh_tomatoes.py"
Each instance passes the Title, Storyline, Poster and Youtube URL of the movie to the constructor that gets called when the object gets instantiated.
3. The file "fresh_tomatoes.py" defines the function open_movies_page() and the various styling(CSS) and layout(HTML) aspectsof the webpage.

Note: fresh_tomatoes.py and media.py both have been imported into entertainment_centre.py using import statements but are not a part of the Python Standard Library.

# Steps to execute the code
1. Make sure that the three files are present under the same Folder in the Python directory in your system.
2. Launch the entertainment_centre.py file
3. Run using F5 key
4. This should launch the Python Shell
5. Also, it would lauch the Movie Trailer Website.

Alternatively, one can also launch the website directly from the fresh_tomatoes.html file that would be created on successfully running the code once using the above steps.

# Expected result:
The website should list out a total of 6 movies, and on clicking on each, user should be able to view the trailer of that movie. 
