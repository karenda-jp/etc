
### "jp-rakuten rch" & "jp-abematv" & "jp-iptv(test)" & "jp-tver" MIX 　guides.xml
~~~
#EXTM3U url-tvg="https://github.com/karenda-jp/etc/raw/refs/heads/main/guides.xml"

私の知る限り、日本で出回っているIPTV-m3uリストのEPGほとんどをカバーしてると思います。
編集を直接行いたいので "gz" 行っていません。

EPGの取得・結合・UPが地味にメンドクサイんですよね。。
~~~
[閲覧注意](https://script.google.com/macros/s/AKfycbz4T3WYaOWtB7BJxlo_nVzjkF5SZp4ECinpWwS6Ah6V3WtImRfXavIrdtGKPAxvuLNzmQ/exec?)
<br />

> [!IMPORTANT]
> DRMに関連するチャンネルとDASH(MPD)には興味ありません。排除しています。<br />
> 言われるのも聞かれるのも視界に入るのも不快に感じます。興味ありません。<br />
> 2026-03-01～ fastch v2へ変更します。<br />
> 2026-04-01～ 取得終了するデータ　→　TeNY_jp,ダンスチャンネル_jp<br />
> 2026-04-04～ CH名称変更につき「エンタメ～テレ_jp」→「メ～テレNEXT_jp」へ変更<br />
<br />

> [!WARNING]
> 2026-04-03 16:00～　Youtubeの仕様変更で公開中のmylistを利用出来ません.<br />
> ERROR --> "reason":"ログインして bot ではないことを確認してください"<br />
> 15時28分ごろに大量リクエストを行ったユーザーが原因によるIP-BANです(泣)<br />
> 18時15分　修正プログラムリリース<br />
> リスト内に書いてある通り<br />
>「**短時間に連続でチャンネルを選択するとエラーになります。制御や仕組みを知らないソフトで決して読み込まないで下さい。**」<br />
> 2026-04-05 Youtubeで軽微な仕様変更があったが、数か所の修正で対応済（送信jsonのﾌｫｰﾏｯﾄﾁｪｯｸが強化されたｗ）<br />
<br />

> [!TIP]
> 日本語のtvg-idだと不都合ある様ですが、私の使用アプリには問題ありませんので現状維持しています。<br />
> ※私の作成しているファイルは文字コードutf-8ですので、<br />
> 日本語のtvg-idで問題ある方は**ファイル拡張子を「m3u → m3u8」に変更する**等で回避できるカモ？<br />
<br />

> [!CAUTION]
> 私は日本のテレビが視聴可能な**m3u8ファイルを提供しておりません**<br />
> EPGデータのみです。<br />



~~~

~~~

### 一部のEPGデータで1日ズレたり歯抜けてたり？ 取得ｱﾌﾟﾘ側の不具合です。
### 　※というか、データ破損を防ぐ為の仕様だそうです。(アプリ Tempest-EPG-Generator 確認済)
### 不具合を排除する様に "site_config" 自作して取得していますが :)
### 日付をまたぐ一挙放送等で表示されなかったり。 ｱﾌﾟﾘの挙動は人それぞれです。
### Tver-EPG 直ったと思います（願望）


### 更新不定期　「出来る限り2～3日間隔」　気まぐれ
<br/>

## "">> A Japanese IP address is required to watch <<""

2025-05　Rch側でtvg-idへ使っていたデータに変更がありました。<br/>
私のリストでは、rch_channel-idで対応する事に暫定的に決めました。

![image](https://github.com/user-attachments/assets/c6629db5-6145-4199-b554-32d881f9b9cb)
<br/>
![image](https://github.com/user-attachments/assets/b8a08e60-1907-441b-aa0c-99a5754f7f5e)
<br/>
![image](https://github.com/user-attachments/assets/d26ddab7-b217-48f7-a3d3-d72d9031cf03)
<br/>

