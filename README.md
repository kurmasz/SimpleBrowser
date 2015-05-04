StarterBrowser
==============

Starter code for a CIS 371 project to write a simple web browser.

Begin by renaming 
  * MyURL_Shell as MyURL, and
  * WebTransactionClient_Shell as WebTransactionClient

To compile:  
cd src
javac edu/gvsu/cis371/starterbrowser/*.java

To run (from this directory):
java -cp src edu.gvsu.cis371.SimpleBrowser

I prefer to compile and run unit tests from within an IDE.  If you would like to compile and run the tests 
from the command line, you will need your own copy of the JUnit and Hamcrest jar files.  

Once you have the necessary jar files, you can compile the tests from the test directory like this:
 javac -cp ../src:../junit-4.11.jar:../hamcrest-all-1.3.jar edu/gvsu/cis371/*.java

and run the tests like this:
 java -cp ../src:../junit-4.11.jar:../hamcrest-all-1.3.jar:. org.junit.runner.JUnitCore edu.gvsu.cis371.MyURLTest