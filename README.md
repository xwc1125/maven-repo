# maven-repo

My personal maven repository.

Usage

pom.xml:

    <repositories>
        <repository>
            <id>xwc1125-maven-snapshot-repository</id>
            <name>xwc1125-maven-snapshot-repository</name>
            <url>https://raw.githubusercontent.com/xwc1125/maven-repo/master/repository</url>
        </repository>
    </repositories>

## Install jar to  repository
		for example:
		
		mvn install:install-file -Dfile=/Users/xwc1125/Downloads/libs/slf4j-api-1.6.6.jar -DgroupId=com.xwc1125.log -DartifactId=slf4j-api -Dversion=1.6.6 -Dpackaging=jar -DgeneratePom=true -DcreateChecksum=true
		
		or
		
		mvn install:install-file -Dfile=/Downloads/libs/slf4j-api-1.6.6.jar -DgroupId=com.xwc1125.log -DartifactId=slf4j-api -Dversion=1.6.6 -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=D:\maven\project-Jar\maven-pro  -DcreateChecksum=true
		
