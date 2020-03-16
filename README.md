assembly demo

# command
mvn help:describe -Dplugin=assembly
mvn help:describe -Dplugin=assembly -Ddetail=true
mvn -DdescriptorId=project assembly:single
use mvn install to test assemble, do not use above command.
