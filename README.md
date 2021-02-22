# ZxingQRWriter

下記の形式のCSVからQRコードを生成するソフトです。

```
"出力ファイル名","HEXテキスト"
```

# Exsample CSV

サンプルのCSV内容は下記のとおりです。

```
output000102030405.png,000102030405
output00.png,00
output303132343536.png,303132343536
```

# Exsample Execute

実行方法の例は下記のとおりです。


```
java -jar ZxingQRWriter0.1.0.jar inputCSV.csv
```

# 環境

ZxingQRWriterのビルド環境

```
jdk-15.0.1
pleiades-2020-12-java-win-64bit-jre_20201222
```

zxingのビルド環境

```
apache-maven-3.6.3
core-3.4.2-SNAPSHOT.jar（生成されたファイル）
javase-3.4.2-SNAPSHOT.jar（生成されたファイル）
```