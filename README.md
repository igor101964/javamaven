# Java Maven Project Template

# Developer Workspace

[![Contribute](http://www.appservgrid.com/images/devlogo.svg)](http://www.appservgrid.com/paw3)

# Recipe

FROM [Art2Dec](https://www.appservgrid.com/paw3)

# Commands

| #       | Command           | 
| :------------- |:------------- |
| 1      | `mvn -f ${current.project.path} clean install && java -jar ${current.project.path}/target/*.jar` |

# App output

App output is streamed into a console. Note that if your app expects user input, do not use command but execute jars in the terminal directly.
