# JNPC2302

勉強会のための資料置き場です。ご参加ありがとうございました。  
時間が足りずにはしょった部分が多かったので、資料をご覧いただきながら、ゆっくり試していただけたら幸いです。講義終了後に気づいた誤字など、修正してあります。  

【付記】  
なお、3-6)としてExcelのPower Queryを使ったバージョンをアップしておきました。このレポをダウンロードして解凍した後、3-6)のExcelを開き、「データ」>>「クエリ」>>「すべて更新」をクリックすると、電力データと気象データを突合して整理したものができあがります。少し時間がかかります。データの入っているフォルダを移動させたり、名前を変えたりすると、動きません。  
考え方のおおもとは、講義での説明と変わりませんが、日時を文字列型ではなく、日付・時刻型で突合しました。気象データに電力データをInner Joinしています。個人的には、Rでコードを書いたほうが、後々のメンテナンスもしやすいだろう、と感じました。  
