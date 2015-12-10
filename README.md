# GeoAddress  
Google Maps API v3を使用した住所から座標に変換するシステムです。  

---

## How to use
初期設定では、以下のようなcsvファイルのフォーマットに対応しております。  

```
No.,施設名,住所,座標  
1,hoge小学校,hoge市hoge区hoge1-2-3,  
2,hoge中学校,hoge市hoge区hoge2-3-4,
```

上記のようなデータを持つcsvファイルをドロップすると、下記のようにその住所の座標が末端に追加されるシステムです.　　

```
No.,施設名,住所,座標  
1,hoge小学校,hoge市hoge区hoge1-2-3,49.3355xx, 48.3355xx
2,hoge中学校,hoge市hoge区hoge2-3-4,49.3355xx, 48.3355xx
```

## Note
※ コードきたないです。必要だったので即席で作りました。  
※ 使用してみたいと考えている方がもしいれば、ご相談ください。  
※ Google Maps API を使用する際のAPIキーは各自で設定してください。scriptタグのuri内にあります。  

## Author 
Taiki Fnit Watanabe  

## LICENCE  
MIT  