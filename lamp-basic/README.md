# docker basic LAMP 

## start

```bash
docker-compose up -d
```

[=> http://0.0.0.0/](http://0.0.0.0/)

## overview

凡庸的な LAMP 環境 を構築するためのシンプルな Dockerfile のパッケージ。

それぞれのディレクトリの Dockerfile を編集すると、MySQL と PHP/Apache のバージョンを自由に指定できます。
 
`sql/` ディレクトリに sql データを設置して、`docker-compose.yml` で指定すると初期データとして読み込むことができます。 
