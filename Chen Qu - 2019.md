文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Chen Qu, Liu Yang, W. Bruce Croft, Yongfeng Zhang, Johanne R. Trippas, and
Minghui Qiu. 2019. User Intent Prediction in Information-seeking Conversations.
In Proceedings of the 2019 Conference on Human Information Interaction and
Retrieval (CHIIR ’19). Association for Computing Machinery, New York, NY, USA,
25–33. DOI:https://doi.org/10.1145/3295750.3298924

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3295750.3298924?casa_token=eCvoFHK_2QAAAAAA:UliQQK3_ENSlTiZ7CwQleb0XS8pRTzl948qUpQkPrfGKyClhoTsNdlU0d69_wZZ-5ZESag0JPxY->

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

1.  It is necessary for conversational assistants to accurately identify user
    intent in information-seeking conversations. Only in this way can Cas
    process the information accordingly and use it to provide answers and adjust
    previous answers.

2.  The CAs need to learn and imitate the behavior of human agents.

3.  User intent prediction models can be used to automatically annotate more
    dialog utterances for data analysis and other tasks such as conversational
    answer finding.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Utterance classification using statistical approaches and recently using
    deep learning techniques.

>   **This research focus on user intent prediction in information-seeking
>   conversations. This specific utterance classification task presents unique
>   challenges because of the complexity and diversity of human
>   information-seeking conversations.**

1.  Conversational search.

>   **This research focus on an essential study in conversational search, which
>   is to predict user intent in this information-seeking setting. The finding
>   of this research can help build conversational search systems that can
>   provide enhanced searching experience using predicted user intent.**

1.  Multi-turn Question Answering.

>   **This research focuses on a specific research need for multi-turn QA in the
>   information-seeking setting. The multi-turn QA could be improved if the user
>   intent is correctly identified.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Investigate two aspects of user intent prediction in an information-seeking
setting.

Construct neural classifiers to incorporate context information and achieve
better performance without feature engineering.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

In this paper they studied two approaches to predict user intent in
information-seeking conversations:

1.  First, they user different ML methods with a rich feature set, and perform
    thorough feature importance analysis on both group level and individual
    level, which shows that structural features contribute most in this task.

2.  They constructed enhanced neural classifiers, which outperforms the baseline
    models by a large margin.

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

Implement a effective way to predict user intent in information-seeking
conversations, which is a key part of conversational search.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Research about utterance classification, conversational search and multi-turn
QA. The research about user intent prediction can make progress for these
related works.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Investigate and construct an effective user intent prediction classifier.
