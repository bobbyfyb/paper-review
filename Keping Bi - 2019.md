文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Bi, K., Ai, Q., Zhang, Y., & Bruce Croft, W. (2019). Conversational product
search based on negative feedback. *International Conference on Information and
Knowledge Management, Proceedings*, 359–368.
https://doi.org/10.1145/3357384.3357939

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3357384.3357939?casa_token=yUjFERubz8EAAAAA:7FF99_RLCAtFSKc1nSacu4Ouk5Aul_1sU0QDls5UKThVC65gu3VWKeuqk_ElQI_f12lirj4ucaMV>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

In conversational product search, users may not have clear ideas about what an
ideal item looks like, especially when they have not seen any item, so it is
more feasible to facilitate the conversational search by showing example items
and asking for feedback instead. And it is easier to collect their detailed
feedback on certain properties (aspect-value pairs).

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Conversational search and recommendation.

**This research is different from previous work in that 1) instead of retrieving
answers, they focus on product-seeking conversations; 2) their system just asks
for the users’ fine-grained relevance feedback on a given aspect-value pair.**

Product Search.

**Most work in this line treats product search as a static process, where
one-shot ranking is performed based on a user query. In contrast, they focus on
a dynamic ranking problem where ranking in the next iteration of the
conversation will be refined based on users’ fine-gained feedback on the
non-relevant items.**

Negative feedback.

**Previous studies on negative feedback alone mainly focused on document
retrieval for difficult queries. most previous work on negative feedback only
users result-level non-relevant information, while this research leverage
aspect-value pairs of non-relevant results and focus on product search.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose a conversational paradigm for product search driven by non-relevant
items, based on which fine-gained feedback is collected and utilized to show
better results in the next iteration.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

Proposed an aspect-value likelihood model that can cap with both positive and
negative feedback on the aspect-value pairs, which consists of the aspect
generation model given items and value generation model given items and aspects.

キーワードと定義
----------------

定義は自分で事典などを使って調べること 出典も明記すること

-   キーワード：定義（出典：〇〇事典）

-   キーワード：定義（本論文 p.xx）

その他気づいたこと
------------------

自分の3戦略
===========

今回レビューした論文をお手本にして新しい論文を書くと仮定すると
どのような3戦略が考えられるか

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

Incorporated user’s negative feedback to improve conversational product search.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Conversational search.

Product search.

Feedback in IR.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose a paradigm that incorporate user’s feedback into conversational search.
