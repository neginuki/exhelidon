# exhelidon

Helidon MP のおためし記録

1. 適当なディレクトリで maven コマンドでプロジェクトを作成

```
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=io.helidon.archetypes -DarchetypeArtifactId=helidon-quickstart-mp -DarchetypeVersion=1.4.4 -DgroupId=io.helidon.examples -DartifactId=exhelidon -Dpackage=io.helidon.examples.quickstart.mp
```

1. Eclipse から Maven プロジェクトとして取り込む

Import > Maven > Existing Maven Project

参考：https://helidon.io/docs/latest/#/guides/03_quickstart-mp
