# unofficial-override-selector
override_selector.json弄れない人向け  
とりあえずアップロード先に困ったのでこちらで公開します。  

# 基本的に最新のセレクターはAnk-Pixiv-Toolのものを使用して下さい。
https://github.com/anekos/Ank-Pixiv-Tool/  

目まぐるしく変わるPixivの仕様変更。  
大半はセレクター情報を更新すれば問題が解決するものが多いが、使用頻度が高い私には更新を待つ時間が勿体ない。  
「ダウンロード出来なくなったら即座に更新してしまおう！」位のノリで更新します。  
  
Specification change of Pixiv that changes quickly.  
Most of them solve problems by updating selector information,  
but I have a lot of time to wait for updating to me.  
  
"Update as soon as downloading becomes impossible!"  

# 命名規則（Naming convention）
unofficial_override_selector_**ank pixiv version**_**date**.json  

**ank pixiv version**  
最新バージョンへ更新されてから「セレクター書き換え」が必要になった場合に分りやすくする為に追加。  
自分のAnkPixiv Toolのバージョンが対象バージョンかそれ以前の場合、インポートが必要になります。  
**が、基本的にはダウンロード出来なくなったら最新のセレクターを使用して貰えれば基本大丈夫です。**  
  
Added to make it easier to understand when "selector rewrite" becomes necessary after being updated to the latest version.
If your version of AnkPixiv Tool is the target version or earlier, importing is required.
**Basically it is okay if you can use the latest selector when downloading becomes impossible.**

**date**  
ただの更新日付です。  
ここが新しければ新しいほど最新です。  
  
It's just a renewal date.
The newer this is, the more recent it is.

# 更新履歴
2018/08/12 最終更新  
変更された行の全体的な修正とダウンロードステータスのテキスト表示の復活  
meta.jsonに情報が記録されなくなった問題の修正  
2018/08/12 更新分  
kayamaiさんによる修正版 https://github.com/anekos/Ank-Pixiv-Tool/issues/174#issuecomment-411671597
