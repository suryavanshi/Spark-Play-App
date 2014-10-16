Spark-Play-App
==============
Need separate play download to use the play command - add play-2.2.4 to the path
play new Play-Spark-App
play eclipse - makes it a eclipse project
play clean compile dist
play run - to run the project

Also added twitter Api key to the project, this project 4 examples for Play+MLIB, Play+Twitter etc. The correct example in utils 
has to called from Application.Scala. After running the play app, it has to be opened in the browser and then it starts running 
the Spark code. Spark shell also must be running with 4 threads.

--------------------------------------------------------

Step By Step - 
For Spark - 
cd to Spark-1.0.0
./bin/spark-shell --master local[4] - start spark

For Play - 
cd to - Play-Spark-Scala
play run
