# maven-repo
My personal maven repository.

# Usage
    <distributionManagement>
        <repository>
            <id>softfn-repo</id>
            <url>file:/Users/willben/IdeaProjects/mvn-repo/repository/</url>
            <url>file:E:/IdeaProjects/mvn-repo/repository/</url>
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