
Build a JAR with dependencies packed inside 
```
mvn -DartifactVersion=1.2.0 clean compile package deploy 
```
The idea is to have a simple project, on which we can adds some external dependencies to test security tools (like JFrog's X-ray) reports.