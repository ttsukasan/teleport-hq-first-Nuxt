# teleport-hq-first-Nuxt

https://ttsukasan.github.io/teleport-hq-first-Nuxt/

teleport hqからgithub出力(nuxt)

yarn.lockがないので一度ローカルビルド

エラー

```console
$ yarn install
➤ YN0000: · Yarn 4.1.1
➤ YN0000: ┌ Resolution step
➤ YN0001: │ Error: @lottiefiles/lottie-player@^1.04 isn't supported by any available resolver
➤ YN0000: └ Completed
➤ YN0000: · Failed with errors in 0s 122ms
```

エラー

```console
$ yarn dev 

 FATAL
Vue packages version mismatch:

- vue@2.7.14
- vue-server-renderer@2.7.16

This may cause things to work incorrectly. Make sure to use the same version for both.
```


```
yarn add @nuxt/components consola
```

```
Cannot find module 'node-fetch-native' from ...
```

```
yarn add node-fetch-native
```

画像が表示されない

```
  router: {
    base: '/teleport-hq-first-Nuxt/'
  }
```

https://develop365.gitlab.io/nuxtjs-2.8.X-doc/ja/faq/github-pages/

だめだ

画像をassetでなくstaticに置いてるから、あまりいけてないな

コミットするとnuxt.config.js や package.jsonも元に戻るのか


ghpages カスタムドメインを試す

route53でcnameレコード作成

github pagesの設定でドメイン名をセット

CNAME ファイル作成
