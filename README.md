
### "jp-rakuten rch" & "jp-abematv" & "jp-iptv(test)" & "jp-tver" MIX 　guides.xml
~~~
#EXTM3U url-tvg="https://github.com/karenda-jp/etc/raw/refs/heads/main/guides.xml"

私の知る限り、日本で出回っているIPTV-m3uリストのほとんどをカバーしてると思います。
編集を直接行いたいので "gz" 行っていません。

EPGの取得・結合・UPが地味にメンドクサイんですよね。。

DRMに関連するチャンネルとDASH(MPD)には興味ありません。排除しています。
言われるのも聞かれるのも視界に入るのも不快に感じます。興味ありません。

日本語のtvg-idだと不都合ある様ですが、私の使用アプリには問題ありませんので現状維持しています。

※スペシャプラス_jp 番組終了に伴い、7月で取得終了します。
~~~

## 一部のEPGデータで1日ズレたり歯抜けてたり？ 取得ｱﾌﾟﾘ側の不具合です。
### 　※というか、データ破損を防ぐ為の仕様だそうです。(アプリ Tempest-EPG-Generator 確認済)
## 不具合を排除する様に "site_config" 自作して取得していますが :)
## 日付をまたぐ一挙放送等で表示されなかったり。 ｱﾌﾟﾘの挙動は人それぞれです。

## RCH m3u CM前後で読み込み止まるのは仕様です。再選択要。

https://channel.rakuten.co.jp/

### 更新不定期　気まぐれ
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
