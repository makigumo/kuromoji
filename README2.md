# Deploying to bintray

* update version to non-SNAPSHOT
* deploy

```mvn -s setting.xml -pl kuromoji-core,kuromoji-unidic-kanaaccent,. -DskipDownloadDictionary deploy```

