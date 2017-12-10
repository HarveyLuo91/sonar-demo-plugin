# sonar-demo-plugin

1.edit the sonar-project.properties of project to be analysed and add an attribute like propertiessonar.foolint.reportPath=XXXX (create the file at specified place)

2.add src/MyClass.foo in analysed project(adding some content to the file to make sure that line number is more than line number of each fake issue)