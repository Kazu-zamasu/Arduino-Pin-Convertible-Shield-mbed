1114FN28-Kids-Shiled
==================================
超簡単な概要
#趣旨
mbedなりArduinoなりでArduino Pin Cnvertible の場合に高級なシールドだけじゃなく子供でも遊べる簡単なシールドを作る。  
Lチカでもモーターでも遊べるように。また、コードから制御するのではなく、視覚的、感覚的に分かりやすいVolや照度や温度などで遊べる基本的な制御を学べるボードにする。  
できれば、販売価格は小学校高学年とかその年齢層でもお年玉とか、日頃のプレゼントで買って貰えそうな値段に抑えたい。  

//ピン仕様:Arduinoピン配列に準拠  
ピン仕様はスイッチサイエンス　mbed 1114FN28  
mbed LPC1114FN28  に対応としました。
http://www.switch-science.com/catalog/1714/  

##最終仕様：Rev0
mbed 1114FN28 に対応するのでプロジェクト名自体を変更
###ハード仕様
１）ボリュームによるアナログ入力  
２）LED２個（5v抵抗あり）緑・赤  
３）最大９A　MOS-FET(モータドライバ兼用） 
４）フォトICによる照度のアナログ入力  
５）サーミスタによる温度のアナログ入力  
６）タクトスイッチ２個によるデジタル入力  
７）トグルスイッチによるデジタル入力  


##改訂前  
####ハード仕様（must)  
1)可変抵抗２つ（ノブ付）  
2)フォトトランジスタ１つ  
3)LED4つ  赤・青・緑・黄
4)最大3V、2Aのモータドライバ出力2つ（FA130、3VStall電流値より）  
5)サーミスター２つ  
6)単３電池ボックス  
7)3Pスイッチ1つ、2Pスイッチ1つ  

####ハード仕様(Addtional)  
1)電圧入力を入れる場合は逆接保護回路  
2)全てリード部品にて接続。なるべく表面実装を避ける  
3)可能なら7セグ  
4)
な感じ。適時アプデします。 
上記のAuduinoシールドはこれをクローズしたら考えます。
