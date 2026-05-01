# plantuml-template

## 生成

PlantUML は graphviz に依存する:

```sh
sudo apt install graphviz
```

※ 日本語向け

```sh
sudo apt install fonts-noto-cjk
```

mise タスク経由で SVG を生成:

```sh
mise run plantuml:generate          # SVG を out/ に生成
mise run plantuml:generate png      # PNG を出したい時
```

`*.puml` を変更すると mise の sources/outputs 連動で再生成される。

