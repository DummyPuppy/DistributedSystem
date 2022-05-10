
for part 1, the most frequently used linux command line tools are

##Project 5
##Create a jar file
$jar -cvf temperature.jar -C  ./  .
##Remove a jar file
Rm staff.jar

##Compile java
javac -classpath  /usr/local/hadoop/hadoop-core-1.2.1.jar:./ -d ./ MaxTemperatureMapper.java

javac WordCount.java -cp $(hadoop classpath) 

##Copy a file 
Cp -original_file -end_folder

##Part 1 task 0 jar compilation line
Hadoop jar wordcount.jar org.myorg.WordCount /user/studentxxx/input/words.txt /user/studentxxx/output 
hadoop dfs -getmerge /user/student246/output ~/Task0Output/

##Add file from local to closer
$sftp userID@heinz-jumbo.heinz.cmu.local
sftp>put MaxTemperature.java [cluster directory]
sftp>get MaxTemperature.java

##Remove everything 
rm -r ./*

Task1
hadoop dfs -getmerge /user/student246/output/task1output /home/student246/Project5/Part_1/Task1/Task1Output/
hadoop dfs -getmerge /user/student246/output/task1output ~

Task2 
javac -classpath  /usr/local/hadoop/hadoop-core-1.2.1.jar:./ -d ./ FactCount.java
 javac FactCount.java -cp $(hadoop classpath) 
hadoop jar factcount.jar org.myorg.FactCount /user/student246/public/words.txt /user/student246/output/t2

Task3
 package edu.cmu.andrew.mm6;
User/
Task4 
javac -classpath  /usr/local/hadoop/hadoop-core-1.2.1.jar:./ -d ./ MinTemperatureMapper.java
javac -classpath  /usr/local/hadoop/hadoop-core-1.2.1.jar:./ -d ./ MinTemperatureReducer.java
javac -classpath  /usr/local/hadoop/hadoop-core-1.2.1.jar:./ -d ./ MinTemperature.java

Task5
jar -cvf rapesplusrobberies.jar -C . .
hadoop jar rapesplusrobberies.jar cmu.edu.zhengzen.RapeAndRobberies /user/student246/public/P1V.txt /user/student246/output/t5
