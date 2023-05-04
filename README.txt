This is the Github project for paper: 
Zhong, Z., Yuan, X., Liu, S. et al. Machine learning prediction models for prognosis of critically ill patients after open-heart surgery. Sci Rep 11, 3384 (2021).https://doi.org/10.1038/s41598-021-83020-7



About the win10 software mentioned in in paper : There are 3 items here:
1: "download link.txt" contains the download link of our Windows 10 software (mainly)
2: "tutorial for user.docx" contains basic tutorial for this software (mainly)
3: "Souce files of XGBoost.zip" contains the XGBoost model files (.model), which were outputted by python 3 machine learning package called sklearn(version:scikit_learn:0.20.3; joblib:0.16.0;sklearn:0.0)


------------------------------------------------------------------------------------------------------------------
!!!!!About the website version of prediction model!!!!!
The service of website will not be maintained by us anymore (It is not online now), because of the cost of maintaining website.
However, user still can find the source code of the website below, and deploy the website and serivce by themself!
------------------------------------------------------------------------------------------------------------------


About the open source website build files:
1) "java-web.zip" is the source code of the website above.
2) "java-web-1.0-SNAPSHOT.7z.001" & "java-web-1.0-SNAPSHOT.7z.002" are the volumn compression of file "java-web-1.0-SNAPSHOT.jar", 
which is a JAR file of 1) project code file packaged by MAVEN and can be executed by java directly.
3) "linux-package.7z.001" & "linux-package.7z.002" are the volumn compression of document file "linux-package".
User can 
A) copy the "linux-package" into path "/usr/src" in Linux service.
B) make sure the firewall of service is close.
C) execute a Linux command "java -jar java-web-1.0-SNAPSHOT.jar" to deploy the website.
D) Access the website with a browser at this URL: (Linux service IP):8111/pages/Home.html
