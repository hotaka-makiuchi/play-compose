# DockerでPlay

ホストで以下を実施する。
Dockerの使えるメモリを4GBにあげておく。
コンテナでプロジェクト *hello* を作成する

```bash
sbt new playframework/play-scala-seed.g8 --name=hello
```

```bash
cd hello
sbt run
```

ブラウザから動作確認
http://localhost:9000


