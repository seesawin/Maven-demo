# Maven-demo
--------------------------------------------
## basic
## mvn -B archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DgroupId=com.mycompany.app -DartifactId=Maven-demo
## mvn install : 成為local jar檔
## mvn clean
## mvn eclipse:eclipse (mvn jar:jar; mvn war:war)
## mvn process-resources : 替換字串(from properties or filters)

--------------------------------------------
## 測試報告(要有junit)
## mvn test : 測試 (mvn test-compile : 只包class檔)
## mvn clean test
## mvn site
## mvn surefire-report:report -Dmaven.test.skip=false: 產生測試報告

--------------------------------------------
## 編譯、打包
## mvn compile : 下載dependance
## mvn clean package -Dmaven.test.skip=true : 包jar, war...

--------------------------------------------
## jmeter-maven-plugin使用
## mvn verify

--------------------------------------------
## Jenkins 
## C:\Users\seesaw\.jenkins\secrets\initialAdminPassword
## java -jar jenkins.war
## Browse to http://localhost:8080
