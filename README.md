# quarkus-getting-started
Quarkus - Creating Your First Application

## bootstrap
```
mvn io.quarkus:quarkus-maven-plugin:1.3.0.Final:create \
    -DprojectGroupId=org.acme \
    -DprojectArtifactId=getting-started \
    -DclassName="org.acme.quickstart.GreetingResource" \
    -Dpath="/hello"
mv getting-started/pom.xml getting-started/src/ .
rm -rf getting-started/
```
