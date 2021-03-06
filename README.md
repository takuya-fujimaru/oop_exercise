# Javaオブジェクト指向 演習問題

Eclipse上で java_oop_exプロジェクトを作成して課題に取り組んでください。

<br>

## 演習1
Enshu1クラスに、非staticなsayHello()メソッド（引数なし／戻り値なし）を定義し、"Hello"を出力するように処理を記述する。また、同じクラスにmain()メソッドを用意し、その中でEnshu1クラスのインスタンスを生成した後、sayHello()メソッドを呼び出して"Hello"を画面に出力しなさい。

<br>

[解答例](/ans/01.md)

<hr>

## 演習2
Enshu2クラスに、非staticなdisplayNumber()メソッド（引数int型／戻り値なし）を定義し、引数を出力するように処理を記述する。また、同じクラスにmain()メソッドを用意し、ローカル変数（int a）を用意し、好きな数字を代入する。次にEnshu2クラスのインスタンスを生成した後、displayNumber()メソッドの引数にaを渡して、aの値を画面に出力しなさい。

<br>

[解答例](/ans/02.md)


<hr>

## 演習3
Enshu3クラスに、非staticなgetNumber()メソッド（引数なし／戻り値int型）を定義し、0以外の好きな数字を返却するように処理を記述する。また、同じクラスにmain()メソッドを用意し、その中でローカル変数（int a）を用意し0で初期化する。次にEnshu3クラスのインスタンスを生成し、getNumber()メソッドを呼び出して、返却された値を変数aに代入する。その後、aの値を画面に出力しなさい。

<br>

[解答例](/ans/03.md)


<hr>

## 演習4
Enshu4クラスに、非staticなtwice()メソッド（引数int型／戻り値int型）を定義し、引数を2倍して返却するように処理を記述する。また、同じクラスにmain()メソッドを用意し、その中でローカル変数（int aとint b）を用意しaに好きな数字を、bには0を代入する。次にEnshu4クラスのインスタンスを生成し、twice()メソッドの引数にaを渡して、返却された値をbに代入する。その後、bの値を画面に出力しなさい。

<br>

[解答例](/ans/04.md)


<hr>

## 演習5
演習1を修正して、sayHello()メソッド呼び出しを2回記述し、"Hello"を2回画面に出力しなさい。

<br>

[解答例](/ans/05.md)


<hr>

## 演習6
演習3を修正して、main()メソッドにローカル変数（int a）を用意し0で初期化する。次にgetNumber()メソッドを呼び出して、返却された値をaに代入する。さらに、getNumber()メソッドを呼び出して、返却された値をaに加える。その後、aの値を画面に出力しなさい。

<br>

[解答例](/ans/06.md)


<hr>

## 演習7
演習6を修正して、main()メソッドではローカル変数を用いず、System.out.println()の()の中で、getNumber()メソッドを2回呼び出し、それぞれの返却値を加算した結果を画面に出力しなさい。

<br>

[解答例](/ans/07.md)


<hr>

## 演習8
演習4を修正して、main()メソッドにローカル変数（int a）を用意し好きな値で初期化する。次にtwice()メソッドの引数にaを渡して、返却された値をaに代入する。さらに、twice()メソッドの引数にaを渡して、返却された値をaに代入する。その後、aの値を画面に出力しなさい。

<br>

[解答例](/ans/08.md)


<hr>

## 演習9
演習8を修正して、main()メソッドではローカル変数を用いず、System.out.println()の()の中で、twice()メソッドを2回呼び出し、返却値を画面に出力しなさい。

> ＋演算子は使用してはならない。

<br>

[解答例](/ans/09.md)


<hr>

## 演習10
Enshu10クラスに、int型のメンバ変数（変数名：number）を用意する。さらに非staticなadd()メソッド（引数int型が2つ／戻り値なし）を定義し、2つの引数を加算した結果をメンバ変数に代入する（※データの保持）。また、同じクラスにdisplay()メソッド（引数なし／戻り値なし）を用意し、その中ではメンバ変数を画面に出力するような処理を記述する。さらに、同じクラスにmain()メソッドを用意し、その中でEnshu10のインスタンスを生成し、add()メソッドを適当な2つの数字を渡して呼び出し、次にdisplay()メソッドを呼び出して結果を画面に出力しなさい。

<br>

[解答例](/ans/10.md)


<hr>

## 演習11
演習5を修正して、int型のメンバ変数（変数名：count）を用意する。sayHello()メソッドの"Hello"を出力している処理の後に、メンバ変数をインクリメントする。さらに、非staticなdisplayCount()メソッド（引数なし／戻り値なし）を定義し、その中ではメンバ変数を出力するように処理を記述する。main()メソッドでは、sayHello()メソッドを何回か呼び出した後に、displayCount()メソッドを呼び出してHelloを出力した回数を出力しなさい。

<br>

[解答例](/ans/11.md)


<hr>

## 演習12
Enshu12クラスに、int型のメンバ変数（変数名：sum）を用意する。さらに非staticなadd()メソッド（引数int型／戻り値なし）を定義し、受け取った引数の値をメンバ変数に加算するように処理を記述する。また、非staticなget()メソッド（引数なし／戻り値int型）を定義し、メンバ変数を返却するように処理を記述する。main()メソッドを用意し、その中でEnshu12クラスのインスタンスを生成した後、add()メソッドの引数に好きな数字を渡す。その後も何度かadd()メソッドを呼び出す。その際の引数の数字は毎回異なるものでもかまわない。最後にget()メソッドを呼び出してこれまでadd()メソッドで渡した数字の合計が画面に出力されることを確認しなさい。

<br>

[解答例](/ans/12.md)


<hr>

## 演習13
（ブレイクタイム）演習12を修正して、add()メソッドの引数の変数名がsumでない場合は、メンバ変数と同じ名前のsumに変更しなさい。その際、動作が変わらないように必要な箇所を修正しなさい。

<br>

[解答例](/ans/13.md)


<hr>

## 演習14
三角形の成立条件として、"長辺の長さ ＜ 他辺の長さの和"というものがある。Enshu14クラスに、staticなtriangleCheck()メソッド（引数int型が3つ／戻り値boolean型）を定義し、3つの引数の中から最大値を探し（長辺）、さらにその最大値が他の変数の和よりも小さいことを確認し、三角形の成立条件を満たす場合はtrue、満たさない場合はfalseを返却するように処理を記述する。main()メソッドを用意し、その中でEnshu14クラスのtriangleCheck()メソッドの引数に好きな数字を渡して、返却された値がtrueなら"三角形として成立します"、falseなら"三角形として成立しません"と画面に出力しなさい。

> main()メソッド内でEnshu14クラスのインスタンスを生成してはならない。また、true／falseを記述してはならない。

<br>

[解答例](/ans/14.md)


<hr>

## 演習15
Enshu15クラスに、staticなisEven()メソッド（引数int型／戻り値boolean型）を定義し、引数が偶数であればtrue、奇数であればfalseを返却するように処理を記述する。main()メソッドを用意し、int型の1次元配列を用意し、好きな数字を好きなだけ用意する。用意した配列のすべての値をEnshu15クラスのisEven()メソッドに1つずつ渡して、返却された値がtrueなら"%1は偶数です"、falseなら"%1は奇数です"とすべての用意した数字について画面に出力しなさい。

> main()メソッド内でEnshu15クラスのインスタンスを生成してはならない。また、true／falseを記述してはならない。

<br>

[解答例](/ans/15.md)


<hr>

## 演習16
Enshu16クラスに、staticなdivine()メソッド（引数なし／戻り値boolean型）を定義し、Mathクラスのrandom()メソッドを呼び出し、返却値である実数を10倍して、さらにint型にキャストした値が奇数なら大吉を表すtrue、偶数なら大凶を表すfalseを返却するように処理を記述する。main()メソッドでは、Enshu16クラスのdivine()メソッドを呼び出し、大凶なら"もう１回！"を出力して、大吉が出るまで繰り返す。大吉が出たら"大吉だ～！"と画面に出力しなさい。

> main()メソッド内でEnshu16クラスのインスタンスを生成してはならない。また、true／falseを記述してはならない。

> 参考：Mathクラスのrandom()メソッドは、0.0以上1.0未満の実数をランダムで返却するメソッドです。<br>ヒント：int a = (int)(Math.random() * 10);

<br>

[解答例](/ans/16.md)


<hr>

## 演習17
Enshu17クラスに、メンバ変数（変数名：number）を用意し、任意の値で初期化する。さらにeven()メソッド（引数なし／戻り値なし）を定義し、メンバ変数を表示した後、メンバ変数を2で割ってメンバ変数を上書きする。また、odd()メソッド（引数なし／戻り値なし）を定義し、メンバ変数を表示した後、メンバ変数を3倍して1加算してメンバ変数を上書きする。さらに、getNumber()メソッド（引数なし／戻り値int型）を用意し、メンバ変数を返却する処理を記述する。main()メソッドを用意し、その中でEnshu17クラスのインスタンスを生成した後、getNumber()メソッドの戻り値が1になるまで繰り返す処理を用意し、その中でgetNumber()メソッドの戻り値が偶数ならeven()メソッドを、奇数ならodd()メソッドを呼び出す。繰り返し処理が終わった後に、Enshu17クラスのメンバ変数を表示し、画面上に表示される値が最終的に1になることを確認しなさい。

<br>

[解答例](/ans/17.md)


<hr>

## 演習18
演習17を修正し、display()メソッド（引数なし／戻り値なし）を用意し、even()メソッド、odd()メソッド、main()メソッドの中から、メンバ変数を出力する処理をdisplay()メソッド呼び出しに変更し、結果が変わらないことを確認しなさい。

<br>

[解答例](/ans/18.md)


<hr>

## 演習19
Pointクラスを作成し、x座標とy座標を保持するためのメンバ変数2つ（int型のxとy）を用意する。また、int型の引数を2つもつコンストラクタを用意し、引数をそれぞれメンバ変数に代入する。さらにPointクラスにはshowArea()メソッド（引数なし／戻り値なし）を用意し、座標(0, 0)と座標(x, y)からなる四角形の面積を表示する処理を記述する。別途Enshu19クラスを用意し、その中でmain()メソッドを定義し、Pointクラスのインスタンスを生成し、その際に適当な数字を2つ引数に渡す。その後、showArea()メソッドを呼び出し、面積を表示しなさい。

<br>

[解答例](/ans/19.md)


<hr>

## 演習20
演習19で作成したPointクラスを修正して、showArea()メソッドの名前をgetArea()メソッドにし、戻り値（int型）を設ける。別途Enshu20クラスを用意し、その中でmain()メソッドを定義し、Pointクラスのインスタンスを2つ生成する（p1とp2）。それぞれのインスタンスを用いてgetArea()メソッドを呼び出し、それぞれの戻り値を比較して、p1がp2よりも大きければ、"p1はp2よりも面積が%1だけ大きい"、p2がp1よりも大きければ、"p2はp1よりも面積が%1だけ大きい"、それ以外の場合は、"p1とp2の面積はどちらも同じ"と表示しなさい。

> %1には面積の差が整数で表示されるようにすること

<br>

[解答例](/ans/20.md)


<hr>

## 演習21
Enshu21クラスに、引数の絶対値を返すstaticなabsoluteValue()メソッド（引数int型／戻り値int型）を用意する。さらにstaticなgetNumber()メソッド（引数なし／戻り値int型）を用意し、その中でMathクラスのrandom()メソッドを使って、-50～50までの数字を返却する処理を記述する。main()メソッドでは、Enshu21クラスのgetNumber()メソッドを呼び出し、その戻り値をint型の変数valueに代入する。次にvalueをabsoluteValue()メソッドの引数に渡し、その戻り値とvalueを使って、以下のような表示例と同じ形式で画面に出力しなさい。

**実行結果（例）**

```
-30の絶対値は、30です。
```

<br>

> Mathクラスのrandom()メソッドを使って-50～50までの乱数を返却するには以下のようにする。<br>ヒント：((int)(Math.random() * 101) - 50)

<br>

[解答例](/ans/21.md)


<hr>

## 演習22
演習19と演習21を組み合わせて、座標が負の値でも面積が正の整数として表示されるように修正しなさい。

<br>

[解答例](/ans/22.md)


<hr>

## 演習23
演習20で作成したPointクラスにgetArea()メソッド（引数int型2つ／戻り値int型）を用意（オーバーロード）し、座標(第1引数, 第2引数)と座標(x, y)からなる四角形の面積を表示する処理を記述する。Enshu23クラスのmain()メソッドでは、Pointクラスのインスタンスを生成した後、引数のないgetArea()メソッドと引数のあるgetArea()メソッドの両方を呼び出し、正常に動作することを確認しなさい。

<br>

[解答例](/ans/23.md)


<hr>

## 演習24
Telephoneクラスに、電話番号を表すprivateなint型のnumber変数と電話番号を設定するコンストラクタ（引数1つ）と電話をかけるcall()メソッド（引数int型／戻り値なし）を用意する。call()メソッドでは、フィールドのnumberと引数を比較し、同じ値の場合は「電話できません」と表示し、異なる値の場合は「○○に電話しています…」（○○は引数の値）と表示する。次にTelephoneクラスを継承するPortableTelephoneクラスにコンストラクタ（引数1つ）を用意し、コンストラクタでは引数を親クラスに渡す。Enshu24クラスのmain()メソッドでは、PortableTelephoneクラスのインスタンスを生成した後、call()メソッドを呼び出す際に適当な値を渡し、2種類のメッセージ（「電話できません」、「○○に電話しています…」）の表示を確認しなさい。

<br>

[解答例](/ans/24.md)


<hr>

## 演習25
演習24で作成したPortableTelephoneクラスにprivateなString型のmailAddress変数とsendMail()メソッド（引数String型2つ／戻り値なし）を用意する。引数を1つもつコンストラクタは引数2つ（int型, String型）に変更し、int型の引数を親クラスに渡し、String型の引数はフィールドのmailAddressに保持する。sendMail()メソッドは、第1引数（送信先のメールアドレス）と第2引数を（メール本文）を表示する。Enshu25クラスのmain()メソッドでは、PortableTelephoneクラスのインスタンスを生成した後、call()メソッドとsendMail()メソッドをそれぞれ呼び出し正常に動作することを確認しなさい。

<br>

[解答例](/ans/25.md)


<hr>

## 演習26
演習25で作成したPortableTelephoneクラスを継承するSmartPhoneクラスを用意する。SmartPhoneクラスにはコンストラクタ（引数2つ（int型, String型））、takePicture()メソッド（引数なし／戻り値なし）を用意する。takePicture()メソッドでは、「カシャッ」と表示する。Enshu26クラスのmain()メソッドでは、SmartPhoneクラスのインスタンスを生成し、takePicture()メソッドを呼び出しなさい。

<br>

[解答例](/ans/26.md)


<hr>

## 演習27
演習24で作成したTelephoneクラスを継承する公衆電話PublicTelephoneクラスを用意する。PublicTelephoneクラスには、int型のmoney変数とコンストラクタメソッド（引数1つ）とaccept()メソッド（引数int型／戻り値なし）を用意する。accept()メソッドは引数で受け取った値をmoneyに加算する。call()メソッドはTelephoneクラスのcall()メソッドの機能を維持しつつ、フィールドのmoneyが10以上なら「○○に電話します…」と表示し、10未満なら「電話できません」と表示するようにオーバーライドする。Enshu27クラスのmain()メソッドでは、PublicTelephoneクラスのインスタンスを生成し、まずcall()メソッドを呼び出し、次にaccept()メソッドを呼び出した後、ふたたびcall()メソッドを呼び出すことによって、正常に動作することを確認しなさい。

<br>

[解答例](/ans/27.md)


<hr>

## 演習28
Enshu28クラスにmain()メソッドを用意し、main()メソッドではTelephone配列（要素数4）を用意し、TelephoneクラスとPortableTelephoneクラス、SmartPhoneクラス、PublicTelephoneクラスのインスタンス（numberはすべて異なる）を作成し、各インスタンスをTelephone配列に保持する。for文を用いてTelephone配列の1つひとつの要素にアクセスしながら、各インスタンスのcallメソッドを呼び出しなさい。また、sendMail()メソッドは同じように呼び出せないことを確認しなさい。

<br>

[解答例](/ans/28.md)


<hr>

## 演習29
ElectricAppliance抽象クラスを用意し、電源の状態を表すboolean型のonPower変数と製品名を表すString型のapplianceName変数、applianceNameを設定するコンストラクタ（引数String型）、電源のオンとオフを切り替えるturnPowerメソッド（引数なし／戻り値なし）、applianceNameを返すgetApplianceName()メソッド（引数なし／戻り値String型）を用意する。turnPowerメソッドは抽象メソッドとして定義する。演習24で作成したTelephoneクラスをElectricApplianceクラスのサブクラスとし、それに伴い各クラスのコンストラクタを修正する。turnPower抽象メソッドは、TelephoneクラスでフィールドのonPowerがfalseならtrueにし、trueならfalseになるように実装する。Enshu29クラスにmain()メソッドを用意し、main()メソッドではArrayList <Telephone>型のtelephones変数を用意しArrayListクラスのインスタンスを生成する。さらに、TelephoneクラスとPortableTelephoneクラス、SmartPhoneクラス、PublicTelephoneクラスのインスタンス（numberとapplianceNameはすべて異なる）を作成し、各インスタンスをtelephones変数に追加する。for文を用いてtelephones変数内の要素に1つずつアクセスしながら、各インスタンスのgetApplianceName()メソッドを呼び出し、その戻り値を表示しなさい。

<br>

[解答例](/ans/29.md)


<hr>

## 演習30
MobileItemShopクラスは、中古の携帯電話（PortableTelephone）を1台10,000円で買い取ってくれる。MobileItemShopクラスにArrayList<PortableTelephone>型のitems変数を用意し、ArrayListクラスのインスタンスを生成しておく。さらにpurchase()メソッド（引数PortableTelephone型／戻り値int型）を用意し、引数をフィールドのitemsに追加し、10,000円を返却する。Enshu30クラスにmain()メソッドを用意し、main()メソッドではMobileItemShopクラスのインスタンスを生成し、TelephoneクラスとPortableTelephoneクラス、SmartPhoneクラス、PublicTelephoneクラスの各インスタンスをpurchase()メソッドに渡す。その際、TelephoneとPublicTelephoneのインスタンスだけが渡せないことを確認しなさい。

<br>

[解答例](/ans/30.md)


<hr>

## 演習31
MobileItemShopは、中古の携帯電話の内、スマートフォンは1台20,000円で買い取ることにした。MobileItemShopクラスのpurchase()メソッドでは、受け取った引数がSmartPhoneインスタンスの場合は20,000円を返却し、それ以外は10,000円を返却する。Enshu31クラスにmain()メソッドを用意し、main()メソッドではMobileItemShopクラスのインスタンスを生成し、PortableTelephoneクラス、SmartPhoneクラスの各インスタンスをpurchase()メソッドに渡し、それぞれの戻り値を確認しなさい。

<br>

[解答例](/ans/31.md)


<hr>

## 演習32
PushPhoneインタフェースとDialPhoneインタフェースを用意する。PushPhoneインタフェースにはpush()メソッド（引数int型／戻り値なし）、DialPhoneインタフェースにはdial()メソッド（引数int型／戻り値なし）を定義する。演習31までに作成してきたPublicTelephoneクラスはPushPhoneインタフェースとDialPhoneインタフェースを実装し、PortableTelephoneクラスはPushPhoneインタフェースを実装する。PublicTelephoneクラスのpush()メソッドでは「公衆電話の○番を押す」と表示し、dial()メソッドでは「公衆電話の○番を回す」と表示する。PortableTelephoneクラスのpush()メソッドでは「携帯電話の○番を押す」と表示する。Enshu32クラスにmain()メソッドを用意し、main()メソッドではPublicTelephoneクラスとPortableTelephoneクラス、SmartPhoneクラスのインスタンスを生成し、それぞれのpush()メソッドを呼び出す。また、PublicTelephoneクラスのインスタンスはdial()メソッドも呼び出しなさい。

<br>

[解答例](/ans/32.md)


<hr>

## 演習33
演習32で使ったSmartPhoneクラスのpush()メソッドを「スマートフォンの○番をタッチする」と表示するように実装する。Enshu32クラスにmain()メソッドを用意し、main()メソッドではArrayList<PushPhone>型の変数phonesを用意し、ArrayListのインスタンスを生成する。PublicTelephoneクラスとPortableTelephoneクラス、SmartPhoneクラスのインスタンスを生成し、ArrayListに追加する。for文を用いて、phones変数内の要素に1つずつアクセスしながら、各インスタンスのpush()メソッドを呼び出しなさい。

<br>

[解答例](/ans/33.md)


<hr>

## 演習34
演習33までで使ったTelephoneクラスにgetNumber()メソッド（引数なし／戻り値int型）を用意し、フィールドのnumberを返却する。SmartPhoneクラスにshowNumber()メソッド（引数なし／戻り値なし）を用意し、getNumber()メソッドを呼び出し、その戻り値を表示する。Enshu34クラスにmain()メソッドを用意し、main()メソッドではSmartPhoneクラスのインスタンスを生成し、showNumber()メソッドを呼び出し、インスタンス生成時に設定した番号が表示されることを確認しなさい。

<br>

[解答例](/ans/34.md)


<hr>

## 演習35
演習34で作成したgetNumber()メソッドを削除し、フィールドのnumberのアクセス修飾子をprotectedにする。このとき、SmartPhoneクラスのshowNumber()メソッドの処理を修正し、演習34同様Enshu35クラスにmain()メソッドを用意し、main()メソッドではSmartPhoneクラスのインスタンスを生成し、showNumber()メソッドを呼び出し、インスタンス生成時に設定した番号が表示されることを確認しなさい。

<br>

[解答例](/ans/35.md)


<hr>

## 演習36
演習35で作成したElectricApplianceクラスにはjp.co.sample パッケージを使用し、TelephoneクラスとPushPhoneインタフェース、DialPhoneインタフェースには、jp.co.sample.standard.telecommunicationパッケージを使用し、PublicPhoneクラスはjp.co.sample.standard.telecommunication.wireパッケージを使用し、PortablePhoneクラスとSmartPhoneクラスにはjp.co.sample.standard.telecommunication.wirelessパッケージを使用した場合、それに伴い正しく動作するように修正しなさい。

<br>

[解答例](/ans/36.md)


<hr>

## 演習37
演習36でパッケージを使ったことにより、メンバ（フィールド、メソッド）へのアクセスが適切に制限できていないため、アクセス修飾子を見直し、適切な制限に修正しなさい。

<br>

[解答例](/ans/37.md)

<hr>
