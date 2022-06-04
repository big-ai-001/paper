# Attention Is All You Need

## 動機[1]

RNN(LSTM、GRU)在當時2017年，是建構先進效能序列模型(NLP：翻譯、分類、QA、摘要)的主要方法，RNN並行問題拖慢速度。

## 回顧[2]

### 取代RNN的方法 --> CNN(卷積)

[Can Active Memory Replace Attention?](https://arxiv.org/pdf/1610.08613.pdf)

[Neural Machine Translation in Linear Time](https://arxiv.org/pdf/1610.10099.pdf)

[Convolutional Sequence to Sequence Learning](https://arxiv.org/pdf/1705.03122.pdf)

[**卷積的問題**](https://youtu.be/ugWDIIOHtPA?t=192)

### 注意力機制（intra Attention）

內積法(Dot-Product Attention)：

加法(Additive Attention):

[Attention 參考資料](https://lilianweng.github.io/posts/2018-06-24-attention)

[seq2seq Attention](https://youtu.be/ZjfjPzXw6og?t=3743)

## 方法[2]

### self-attention

*計算複雜度
*可並行化
*長距離依賴

### why scale

softmax

### why  Multi-Head

投影單空間VS投影多空間(更大的representation space)

### Position

why need Position

## 結果[1]

請參考論文，尋找支持以下假設的實驗數據：

* Transformer 擁有比 RNN 更高的運算效率(平行運算優勢)
* Transformer 的表現應近似 RNN

## 貢獻[1]

請參考論文，論文中實驗的方法對社會有甚麼貢獻。

*IF 好，好在哪?提供應用方向(大家怎麼用)

*IF 不好，不好在哪?提供改善方向(大家怎麼改)

<!-- 論文的動機、簡述過去相關研究、研究方法、結果、貢獻。 -->