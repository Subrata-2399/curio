Create a Directory for Your Project :

mkdir ErrorLogMonitoring
cd ErrorLogMonitoring


Create Java Files :
Save this code in a file named LogEntry.java inside the ErrorLogMonitoring directory.
Save this code in a file named ErrorLogMonitor.java inside the ErrorLogMonitoring directory.
Save this code in a file named Main.java inside the ErrorLogMonitoring directory.


Compile the Java Files :
javac LogEntry.java ErrorLogMonitor.java Main.java


Create the Input File :
1 1715744138011;INTERNAL_SERVER_ERROR;23.72
1 1715744138012;INTERNAL_SERVER_ERROR;10.17
2 INTERNAL_SERVER_ERROR
1 1715744138012;BAD_REQUEST;15.22
1 1715744138013;INTERNAL_SERVER_ERROR;23.72
3 BEFORE 1715744138011
3 AFTER 1715744138010
2 BAD_REQUEST
4 BEFORE INTERNAL_SERVER_ERROR 1715744138011
4 AFTER INTERNAL_SERVER_ERROR 1715744138010




Run the Java Application :
java Main



Check the Output :
cat output.txt




