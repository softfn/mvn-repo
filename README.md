# maven-repo
My personal maven repository.

# Usage

    pom.xml:
    
    <distributionManagement>
        <repository>
            <id>softfn-repo</id>
            <url>file:../mvn-repo/repository/</url>
        </repository>
    </distributionManagement>
    
    <repositories>
        <repository>
            <id>softfn-repo</id>
            <url>https://raw.githubusercontent.com/softfn/mvn-repo/master/repository</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>