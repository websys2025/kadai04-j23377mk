## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。 **クラス全体に関わるデータを扱うため**
* buyItemがインスタンスメソッドである理由を考察せよ。 **このメソッドはitemsの状態に依存するため、インスタンスメソッドが適切。**
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。 **自分自身のインスタンスを指すthisを使用し、購入ボタンを押した瞬間、そのインスタンスを参照することができる。**
* 特定したセルの値をどのように変更するのか説明せよ。 **購入ボタンを押したら、buyItemを呼び出しthis.stock -= 1を実行し、セルの値を変更する。**
### Q4-3. 感想
* 今回の課題で苦労したこと **表の作り方があまりよくわからなかったので、表の作成に苦労した**
* 演習を通して理解できたこと **htmlでの表の作り方や、javaでの「this」の使い方が理解できた**
* この自動販売機プログラムの追加機能や課題など **商品の補充機能を追加するといいと思う。**
