# maven

Use it as a note for learning maven

![](./images/Screen%20Shot%202022-04-09%20at%203.20.48%20AM.png)

## How to build a maven project step by step

### Project location folder

1. mvn archetype:generate
2. (... default)
3. 'groupId': com.seaboyz(package name)
4. 'artifactId': maven(project name)
5. <packaging>jar</packaging> or <packaging>war</packaging>
   ![](./images/Screen%20Shot%202022-04-09%20at%203.59.50%20AM.png)
   a. jar for java application
   b. war for webapp

### Build process

1. mvn compile
2. mvn package
3. java -cp target/maven-1.0-SNAPSHOT.jar com.seaboyz.App (run the java jar file and the class name)

### Maven structure

![](./images/Screen%20Shot%202022-04-09%20at%204.31.59%20AM.png)
