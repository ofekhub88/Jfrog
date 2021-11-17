## For  java 1.8
wget https://downloads.apache.org//db/derby/db-derby-10.15.2.0/db-derby-10.15.2.0-bin.zip

java -jar lib/derbyrun.jar ij
connect 'jdbc:derby:$JFROG_HOME/artifactory/var/data/artifactory/derby/;create=true';
