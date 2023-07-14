# okabe_jobchange
データ分析コンペティションサイト「SIGNATE」のコンペ「医療保険の費用帯予測」にて使用したPythonコードになります。
コンペURL：https://signate.jp/competitions/751

■ファイル説明
・医療保険の費用帯予測Optuna-3.ipynb
OptunaにてハイパーパラメータをチューニングしたLightGBMにて予測
・医療保険の費用帯予測-ランダムフォレスト3.ipynb
GridSearchCVにてハイパーパラメータをチューニングしたランダムフォレストにて予測
・医療保険の費用帯予測-Pycaret.ipynb
Pycaretにて自動学習
ロジスティック回帰が選ばれる
・医療保険の費用帯予測_アンサンブル.ipynb
上記3つの分析から得られた結果を平均したものを結果として出力

・医療保険の費用帯予測-Pycaret2-アンサンブル.ipynb
Pycaretにて自動学習し、上位3つをアンサンブルして結果として出力
