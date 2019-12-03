# drools

How to set everything up for the Workshop
You can either use Eclipse or IntellijIDEA

A. Setting up project with Eclipse:
1. install Eclipse IDE, choose Eclipse IDE for Java Developers
2. go to https://github.com/sebivenlo/drools, click on “clone or download”, copy URL
3. click on ‘import projects’- Git- projects from Git-next
4. click ‘clone url’-next
5. insert URL at the top-next
6. next-next-next
7. choose ‘import as general project’-next-finish
8. right click on project-configure-convert to Maven project
9. on the top click on help-install new Software
10. at top insert:
 http://download.jboss.org/drools/release/ 7.23.0.Final/org.drools.updatesite/
11. press enter, check box at drools and jbpm-next
12. finish-install anyway
13. Check if it works: open file Src-main-java-io.github(…)-section03-statelesspassport, and
click on “run” and look if it prints “Section 3. Enter step (1...6):”

B. With IntellijIDEA

1. Install IntellijIDEA Ultimate Edition (free for students)
2. go to https://github.com/sebivenlo/drools, click on “clone or download”, copy URL
3. Open Intellij, click on “check out from version control”-git
4. Paste URL,click on clone
5. Click on pop up “add as maven project”
6. If pop up maven projects need to be imported, click on import changes
7. In project folder Open Src-main-java-io.github(…)-section03-statelesspassport
8. There should be a pop up “SDK is not defined”, click on Setup SDK
9. Choose 1.8., if you don’t have it take newest version
10. Check if it works: open file Src-main-java-io.github(…)-section03-statelesspassport, rightclick in code and click on “run” and look if it prints “Section 3. Enter step (1...6):”
