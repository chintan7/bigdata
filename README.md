# bigdata
BigData Assignments 
<br>
<h2> Instructions to Run the code for Assignment 1 </h2>
<ul>
  <li> Clone the repository using Maven or copy directly from Github. You can use the command <b><i> git clone 'link to repository'</b></i></li>
  <li> cd into the folder <b><i>(cd bigdata-assignments/assignment1)</b></i> and run the following command :- <b><i> mvn clean package</b></i></li>
  <li>Finally run the hadoop command to run the DemoWordCount code:- <b><i>hadoop jar target/assignment1-1.0-SNAPSHOT-fatjar.jar edu.umd.chintan7.DemoWordCount -input bible+shakes.nopunc -output wc -numReducers 5 </b></i></li>
  <li> A new folder named 'wc' will be created housing the output files </li>
</ul>
