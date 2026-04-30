
## 自分が使う用にEPGファイル等を作って置いてます！
### "jp-rakuten rch" & "jp-abematv" & "jp-iptv(test)" & "jp-tver" MIX 　guides.xml
**更新不定期　「出来る限り2～3日間隔」　気まぐれ 注意！** <br />

~~~
#EXTM3U url-tvg="https://github.com/karenda-jp/etc/raw/refs/heads/main/guides.xml"

私の知る限り、日本で出回っているIPTV-m3uリストのEPGほとんど(R-18除く)をカバーしてると思います。
編集を直接行いたいので "gz" 行っていません。
通常ｱｯﾌﾟﾛｰﾄﾞの上限値 日数にして5～6日分　25MB未満ﾌｧｲﾙです。

EPGの取得・結合・UPが地味にメンドクサイんですよね。。
~~~


~~~
 Githubにパブリック公開している物ですので、使いたい方は許可なく使って問題ありませんが、
 トラブルや不具合等は言われる覚えはありません。更新すれば5～6日分のﾃﾞｰﾀ量です。
 使う事を辞める判断はご自由にどうぞ(^^;
 もしくは、拾ったm3uの使用しているEPGがウチだった人はコンニチワ～ハジメマシテ！！

 ・ guides.xml ⇒ 色々ミックスした日本向けEPGファイル
 ・ guide_radiko.xml ⇒ ラジオで使えそうな感じのEPGファイル
 ・ EPG_TEST_FILE.m3u8 ⇒ EPGの表示確認用＆ヘッダー作成用ファイルURL部分を手持ちのヤツと入れ替えていくと？？
 ・ Youtube_mylist.m3u8 ⇒ Youtubeの番組をIPTVとして観れたらどうだ？実験的ファイル リスト内の説明を読む事！
　　　　↑ 停止中

  ★ ★
   第2のメインコンテンツ的な「EPG置換君」はTipの項目からどうぞ。強力な置換性を有しています。
   よそからウチのEPGに乗換え用　そこらで拾ったm3uからウチのEPGに一本化とか出来たり出来なかったり、
   使い方(モード)次第で無限大データ更新時にアドレス変更しますので直リンクは厳禁！
   ブックマークは今見てるこのページでね？ 比較的メジャーな所のtvg-idは学習済です！
  ★ ★
~~~

<br />

> [!IMPORTANT]
> DRMに関連するチャンネルとDASH(MPD)には興味ありません。排除しています。<br />
> 言われるのも聞かれるのも視界に入るのも不快に感じます。興味ありません。<br />
> 2026-03-01～ fastch v2へ変更します。<br />
> 2026-04-01～ 取得終了するデータ　→　TeNY_jp,ダンスチャンネル_jp<br />
> 2026-04-04～ CH名称変更につき「エンタメ～テレ_jp」→「メ～テレNEXT_jp」へ変更<br />
> 2026-04-19～ 「BS10プレミアム_jp」　取得先変更・・・。[深夜0時の怪現象を修正しました！](https://tvguide.myjcom.jp/detail/?channelType=120&serviceCode=201_4&eventId=65022&programDate=20260421)
<br />

> [!WARNING]
> 2026-04-30 13:00～　Youtube_mylistのアドレスを変更しました。<br />
>「**2026-04-28 Youtube仕様変更　対応できるまで無期限停止します**」<br />
> <br />
> プレイヤーへアドレス登録している方は更新押すだけで完了されます。<br />
<br />

> [!TIP]
> 日本語のtvg-idだと不都合ある様ですが、私の使用アプリには問題ありませんので現状維持しています。<br />
> ※私の作成しているファイルは文字コードutf-8ですので、<br />
> 日本語のtvg-idで問題ある方は**ファイル拡張子を「m3u → m3u8」に変更する**等で回避できるカモ？<br />
> [EPG置換君](https://script.google.com/macros/s/AKfycbwSKBtqUIxFb8iMmElw6izbpnIqJCMbUvMoMSBfcvCaTl9IYnQl9tOX9os7cpmfTZ_n9A/exec?)<br />

<br />

> [!CAUTION]
> 私は日本のテレビが視聴可能な**m3u8ファイルを提供しておりません**<br />
> EPGデータのみです。<br />



~~~
 一部のEPGデータで1日ズレたり歯抜けてたり？ 取得ｱﾌﾟﾘ側の不具合です。
 　※というか、データ破損を防ぐ為の仕様だそうです。(アプリ Tempest-EPG-Generator 確認済)
 不具合を排除する様に "site_config" 自作して取得していますが :)
 日付をまたぐ一挙放送等で表示されなかったり。 ｱﾌﾟﾘの挙動は人それぞれです。
 Tver-EPG 直ったと思います（願望）

~~~



<br />
<br />

## "">> A Japanese IP address is required to watch <<""

2025-05　Rch側でtvg-idへ使っていたデータに変更がありました。<br/>
私のリストでは、rch_channel-idで対応する事に暫定的に決めました。

![image](https://github.com/user-attachments/assets/c6629db5-6145-4199-b554-32d881f9b9cb)
<br/>
![image](https://github.com/user-attachments/assets/b8a08e60-1907-441b-aa0c-99a5754f7f5e)
<br/>
![image](https://github.com/user-attachments/assets/d26ddab7-b217-48f7-a3d3-d72d9031cf03)
<br/>

