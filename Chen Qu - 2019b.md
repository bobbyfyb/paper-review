文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Qu, C., Yang, L., Qiu, M., Bruce Croft, W., Zhang, Y., & Iyyer, M. (2019). BERT
with history answer embedding for conversational question answering. SIGIR 2019
- Proceedings of the 42nd International ACM SIGIR Conference on Research and
Development in Information Retrieval, 1133–1136.
https://doi.org/10.1145/3331184.3331341

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3331184.3331341?casa_token=_ZX-Jxi1yMMAAAAA:ocum-rxGtgys5K_tanmw3_knjsE_IwayxV9ZUBpW6Q71_h4kbSIqKAalJRrgRASMU6VKEE2okk2P>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

One of the major challenges to multi-turn conversational search is to model the
conversation history to answer the current question. In order to understand the
user’s latest information need, the system should be capable to handle the
conversation history.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Existing methods that tackle the problem of conversation history that
    prepend history turns or mark answers in the passage.

**These methods cannot handle a long conversation history.**

1.  Existing method that users complicated attention mechanisms to model
    history.

**This method generates relatively large system overhead.**

**The method proposed in this paper is conceptually simple, robust, effective,
and has better training efficiency compared to previous approaches.**

1.  Research and datasets released about machine comprehension.

2.  CoQA and QuAC datasets,

>   **This research focus on QuAC.**

1.  Research about conversational search.

>   **This research focus on dealing with conversation history, which is an
>   integral part in the joint effort of building functional conversational
>   search systems.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose a conceptually simple yet highly effective approach referred to as
history answer embedding.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

1.  Introduced a general framework to handle the conversation history in ConvQA,
    laying the groundwork for future efforts with this task.

2.  Proposed a history modeling method which is one of the first attempts to
    model conversation history in a BERT-based model for information-seeking
    conversations.

3.  Performed an in-depth analysis to show the impact of different amounts of
    conversation history, showing that history prepending methods degrade
    dramatically with long history while the method of this paper is robust and
    shows advantages under such a situation, which provides new insights into
    conversation history modeling in ConvQA.

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

When implementing a conversational search system, it is significant to
incorporate the conversation history into the conversation of current turn to
answer current question.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Existing methods that modeling the conversation history.

Research about conversational search and QA system.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose an effective method to model the conversation history.
