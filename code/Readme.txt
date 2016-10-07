Tools:
1.Profiling tool: YourKit Java Profiler 2015 build 15050.
2.IDE:  Eclipse 4.4.2 (Luna) with plugin ADT-23.0.6 (for developing android program)

There are 2 programs in the code folder:
 - Program run on Android (Android folder)
 - Program run on PC (PC folder)

How to run program on PC?
1.Extract the file median filter.zip (in code/PC).
2.Install JDK from http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html.
3.Download eclipse from http://www.eclipse.org/downloads/ and Extract.
4.Open Eclipse, select File -> import -> General -> Existing Projects into Workspace
5.Right at the imported project in Package Explorer, select Run as Java Application.

How to run program on Android?
1.Copy the AndroidMedianFilter.apk in code/Android into android device.
2.Click to install it.
3.Run it from launcher

About Profiling information:
 - There are brief information in the report.
 - To see all profiling information of 147 test cases run on PC
	1.Install YourKit Java Profiler from https://www.yourkit.com/download/.
	2.Open file profiling.snapshot in code/Profiling by the YourKit Java Profiler program.

In PC, you can run all the 147 test cases autonomously by click the button "Autonomous Test".
In Android, you need to run the test separately.
The Experiment Result.txt contains all the raw result of 147 test cases which are the result of the Autonomous Test. 