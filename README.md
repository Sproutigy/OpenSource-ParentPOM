# OpenSource-ParentPOM
Maven Parent POM for Sproutigy Open Source projects

To deploy projects based on this POM (do it on clean project):
```
mvn jgitflow:release-start
mvn jgitflow:release-finish -Possrh-distrib
```