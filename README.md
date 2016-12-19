# Application Container Cloud Service へ Tomcat をデプロイ
---
## 説明

![](http://docs.oracle.com/en/cloud/paas/app-container-cloud/sp_common/shared-images/cloudgs_appcontainer.png)

**Oracle Application Container Cloud Service** は、基盤を Docker とするアプリケーションの実行環境を提供するクラウド・サービスです。

- [Oracle Application Container Cloud Service を使ってみた](http://qiita.com/shinyay/items/0cef960aa435a72a56f8)
- [Application Container Cloud Service を REST API で操作してみた](http://qiita.com/shinyay/items/8cb3aac11b7f86d6e660)

Docker の基盤レイヤにフォーカスせずに、アプリケーションが稼働するスケーラブルな環境をシンプルかつ素早く提供でしている事が特徴です。そのため ***Dockerfile*** や、***docker-compose.yml*** を記述することもなく、シンプルにデプロイするアプリケーションを用意するだけとなります。

- (参考) Docker 基盤を提供するクラウド・サービス: [Oracle Container Cloud Service](https://cloud.oracle.com/container)
  - [マニュアル](http://docs.oracle.com/cloud/latest/container-cloud/index.html)


この Application Container Cloud Service に、Tomcat で稼働する Web アプリケーションを Tomcat ごとデプロイしてみます。
