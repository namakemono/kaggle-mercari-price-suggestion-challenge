# Mercari Price Suggestion Challenge

- https://www.kaggle.com/c/mercari-price-suggestion-challenge/data

メルカリの商品説明から出品価格の推定

## Missions

- 過去問を題材にゴールド圏内のスコアを再現する．

## 制約条件

- Kaggle Kernel環境で学習から推論まで60分以内で実行
- kaggle kernel環境
    - 4cores / 16GB RAM / 1GB disk / GPUなし

## 方針

- スコアがわずかにしか改善しない部分はなるだけ除外する
- なぜそうやってるのかの根拠となるリンクを書く
- コメントをなるだけ多く書く

## 目標値

- 1st: 0.37758
- 14th: 0.40208
- [再現コード](notebook/tfidf-nn-rmsle-0.1701.ipynb): 0.39762 (達成)

## References

- https://www.kaggle.com/lopuhin/mercari-golf-0-3875-cv-in-75-loc-1900-s
- https://copypaste-ds.hatenablog.com/entry/2019/02/15/170121


