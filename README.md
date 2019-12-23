# project-template-generation
This is to create the template of the project

##Step 1:
Clone the repositry

##Step 2:
cd project-template-generation

##Step 3:
mvn clean install

##Step 4:
Go to the directory where you want to create the project.

mvn archetype:generate -DarchetypeGroupId=com.service-provider
    -DarchetypeArtifactId=project-template-generation
    -DarchetypeVersion=1.0.Example
    -DgroupId=your new group id
    -DartifactId=your new artifact Id
    -Dversion=1.0.SANPSHOT
