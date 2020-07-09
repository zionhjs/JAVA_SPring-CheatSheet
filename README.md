# JAVA_SPring-CheatSheet (For Mac only!)
# Create a Java-Spring Project

#1 Install Apache Maven
-To install Maven, first needs to install HomeBrew. Download HomeBrew at https://brew.sh/. 
-In Terminal 
- $ brew install maven
-Check maven version
- $ mvn version
-Now you should see something like this:
![image](https://github.com/zionhung/JAVA_SPring-CheatSheet/blob/master/IMG/Screen%20Shot%202020-07-08%20at%2010.00.30%20PM.png)

#2 Start a New Spring Boot Project
-To start a Spring Project, you need the Following ready:
-Spring Tool Suite set up
-JDK and its environment variables already set up
-Maven and its environment variables already set up

- 2.1 Create an empty folder or directory wherever you want your Spring Boot projects to be located at.(e.g. "xxx/springPlatform")

- 2.2 In Eclipse choose the folder you just created as workspace:
![image](https://github.com/zionhung/JAVA_SPring-CheatSheet/blob/master/IMG/22.png)

- 2.3 In Eclipse -> Project Explore - create new Project -> Choose Spring Starter Project:
![image](https://github.com/zionhung/JAVA_SPring-CheatSheet/blob/master/IMG/cp.png)

- 2.4 In the 'New Spring Starter Project' window, we must fill out information about our project.(Naming the project!)
![image](https://github.com/zionhung/JAVA_SPring-CheatSheet/blob/master/IMG/2.3.png)
Name Field: <yourprojectname>. This will be your project name all lowercased.
Group Field: com.<company>.<yourprojectname>. This will be a combination of your company and your project. For now, you can put your name in its place.
Artifact Field: <yourprojectname>
Description Field: Short description about your project
Package Field: Same as the group field.

- 2.5 Click finish and we'll add our dependencies later from our pom.xml file

************************ Please check pom.xml file to add our dependencies ***************************************************