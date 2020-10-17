
# 忘れやすいことやコマンド

$ git remote add origin git@github.com:ymd65536/android-helloapp.git  

先にリモートリポジトリを作成しておくそうでないと  
> ERROR: Repository not found が表示される  

pushはこれでOK  
$ git push -u origin master  

リモートを修正したらプルしとく  
$ git pull

# はじめの一歩

## チョット、おさらい

- JDKには種類がある
OpenJDKとOracleJDKが存在する。

AndroidStudioでOpenJDKを使う限り  
有償のOracleJDKでの影響は受けない。  

ちなみに現在(2020.10.17)のOracleJDKは30ドルとのこと

- JVM
Java Virtual Machine の略
AndroidStudioで使われているJVMは  
Google独自のJVMがとのこと  
(すごい、Google)



## 開発環境の変わり方

現在(2020.10.17)のAndroidの開発では
プログラミング言語のKotlinが主流らしい。

Java × Eclipse Keplerで開発していた時が懐かしい。

- JavaからKotlinへ
Javaベース開発だったが  
2011年に発表、2012年にOSS化されたKotlinによる開発が流行  

[こちらの記事](https://japan.zdnet.com/amp/article/35157065/)
ではPlayStoreにアップロードされているアプリケーションの70%が  
Kotlinで開発されているとのことそれだけの存在感がKotlinにはある。


