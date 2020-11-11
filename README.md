# Judge_wine_quality
## 日本語
### 初めに
 これはwineの品質を予測するモデルを作成するコードです。
 7段階のワインの品質を予測するモデルと、3段階に分けた精度の高いモデルを作成する。

### 使用方法

1. download_wine_data.py
    + wineのCSVデータをダウンロードする。

2. wine_simple.py
    + 7段階のワインを判別できる簡易的なモデルを作成する。
    結果を確認する

3. count_wine_data.py
    + 格品質がどのくらいあるのか、データ化する。

4. wine_mod_label.py
    + 3 ~ 4 / 5 ~ 7 / 8 ~ 9
    のように3段階に分けて、出力は0,1,2となるようなモデルを作成する。

5. 独自のワインデータを入れたい場合の使用方法は、モデルへの入力に、品質の部分が抜けたwineデータを与えることで、予測が可能となる。

## English
### Introduction.
  Code to create a model to predict wine quality
 We create a model that predicts wine quality with seven levels of accuracy and a model that predicts wine quality with three levels of increased accuracy.

### Usage

1. download_wine_data.py
    + Download wine CSV data. 2.

2. wine_simple.py 
    +  create a simple model to identify the seven levels of wine.

3. count_wine_data.py
    + Data about how much wine is rated.

4. wine_mod_label.py
    + 3 ~ 4 / 5 ~ 7 / 8 ~ 9
    The model is divided into three stages, such that the output is 0, 1, and 2.

5. if you want to include your own wine data, you can use it by giving the input to the model as wine data with the quality part missing, so that you can make predictions.
