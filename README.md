# 群れっぽい動きをシミュレーションしてみた（ボイドモデル）

### 概要
書籍[「作って動かすALife」](https://www.amazon.co.jp/%E4%BD%9C%E3%81%A3%E3%81%A6%E5%8B%95%E3%81%8B%E3%81%99ALife-%E2%80%95%E5%AE%9F%E8%A3%85%E3%82%92%E9%80%9A%E3%81%97%E3%81%9F%E4%BA%BA%E5%B7%A5%E7%94%9F%E5%91%BD%E3%83%A2%E3%83%87%E3%83%AB%E7%90%86%E8%AB%96%E5%85%A5%E9%96%80-%E5%B2%A1-%E7%91%9E%E8%B5%B7/dp/4873118476/ref=sr_1_1?adgrpid=53626124112&amp;hvadid=259131798438&amp;hvdev=c&amp;hvlocphy=1009308&amp;hvnetw=g&amp;hvpos=1t1&amp;hvqmt=e&amp;hvrand=8550447354966873735&amp;hvtargid=kwd-498809778674&amp;jp-ad-ap=0&amp;keywords=%E4%BD%9C%E3%81%A3%E3%81%A6%E5%8B%95%E3%81%8B%E3%81%99alife&amp;qid=1554809467&amp;s=gateway&amp;sr=8-1)の第4章を参考に"群れ"に強化学習を応用しようと試みている。

### 元ネタ
- 「作って動かすALife」の[GitHubのlink](https://github.com/alifelab/alife_book_src)
    - このGitHubでは、上記リンクのコードを改変して使っている。
