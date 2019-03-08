# archetype-generate-maven-plugin
Quick archetype generate command for new maven plugin project

```bash
mvn archetype:generate \
  -DarchetypeGroupId=org.apache.maven.archetypes \
  -DarchetypeArtifactId=maven-archetype-plugin \
  -Dpackage=com.gituhb.daggerok.plugin \
  -DartifactId=kafka-maven-plugin \
  -Dversion=1.0-SNAPSHOT \
  -DgroupId=com.github.daggerok.plugin \
  -B
```
