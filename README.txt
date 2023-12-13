1. Extract All files from AmazonDroneManager.zip
2. Load Apache NetBeans
3. Click on Open Project and go to where you extracted the files
4. Load AmazonDroneManager
5. Go to the Services tab in the top left by Files
6. Right click Java DB and go to Properties
7. Click Browse on Java DB Installation
8. Go to where you extracted the files and click open file on db-derby-10.16.1.1-bin
9. Click Browse on Database Location
10. Got to where you extracted the files and click open file on DerbyDatabases
11. Click OK in Java DB Properties
12. Open the drop down on Java DB and right click AmazonData and click connect
13. For the password and username enter “java” for both
14. Click the drop down on Drivers in Databases and right click Java DB (Network)
15. Click Customize
16. Click the two files in the Driver File(s) and remove them
17. Click Add
18. Go to where the files were extracted and open db-derby-10.16.1.1-bin
19. Go to lib file 
20. And add both derbyshared and derbytools
21. Click OK when both are added




If running version newer then Apache NetBeans IDE 18
1. Right Click the AmazonDroneManager in Projects
2. Go to Resolve Project Problems
3. Click on Resolve
4. Click Downgrade Project Source/Binary Format to 18
5. Hit Ok




Logging in for the first time
UserName: admin
Password: admin