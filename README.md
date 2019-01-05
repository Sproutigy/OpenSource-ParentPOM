# OpenSource-ParentPOM
Maven Parent POM for Sproutigy Open Source projects

To deploy projects based on this POM (do it on clean project):
```
git checkout develop
mvn jgitflow:release-start
mvn jgitflow:release-finish
git push --follow-tags
git checkout master
git push
```