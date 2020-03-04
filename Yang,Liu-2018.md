文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Liu Yang, Minghui Qiu, Chen Qu, Jiafeng Guo, Yongfeng Zhang, W. Bruce Croft, Jun
Huang, and Haiqing Chen. 2018. Response Ranking with Deep Matching Networks and
External Knowledge in Information-seeking Conversation Systems. In The 41st
International ACM SIGIR Conference on Research & Development in Information
Retrieval (SIGIR ’18). Association for Computing Machinery, New York, NY, USA,
245–254. DOI:https://doi.org/10.1145/3209978.3210011

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3209978.3210011?casa_token=_D7euLYAALgAAAAA:TVIWxCq3jeG7Ks8tLXSTcaVBwHUaqnP6K2_-DJdGpvePkLRtsaThTHF7fN2UDOK1KXyA6ds1gzob>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

Model and research findings of this research provide new insights on how to
utilize external knowledge with deep neural models for response selection and
have implications for the design of the next generation of information-seeking
conversation systems.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Research about generation-based methods to build conversational systems

2.  Research about retrieval-based methods to build conversational system, which
    studies response ranking for single-turn conversation

3.  Studies on multi-turn conversation

**Weakness of the researches above:**

-   **Mainly focus on open domain chit-chat conversations or task/transaction
    oriented conversations, less attention has been paid to information oriented
    conversations**

-   **Lack of modeling external knowledge beyond the dialog utterances.**

1.  Research about Pseudo-relevance feedback(PRF) and knowledge distillation.

-   **This research incorporate external knowledge into deep neural models with
    PRF and QA correspondence knowledge distillation.**

1.  Neural ranking models that mainly rely on lexical matching information, via
    modeling semantic match patterns in text.

**Weakness:**

-   **For response ranking in information-seeking conversations, the match
    patterns between candidate responses and conversation context can be quite
    different from the well studied lexical and semantic matching.**

1.  Research about conversational search such as:

    1.  Radlinski and Craswell’s research about theoretical framework of
        conversational search;

    2.  Thomas et al. released the Microsoft Information-Seeking
        Conversation(MISC) data set

    3.  Kenter and de Rijke adopted a conversational search approach to QA

    4.  Arguello et al. studied how the medium affect user requests in
        conversational search

    5.  Spina et al. studied the way of presenting search results over
        speech-only channels to support conversational search

    6.  Yang et al. investigated predicting the new question that the user will
        ask given the past conversational context.

2.  Research about conversation response generation and ranking with deep
    learning and reinforcement learning

3.  Sordoni et al. proposed a neural network architecture for response
    generation that is both context-sensitive and data-driven utilizing the RNN
    Language Model architecture.

4.  Wu et al. proposed a sequential matching network that matches a response
    with each utterance in the context on multiple levels of granularity to
    distill important matching information.

-   **This research is a retrieval-based method, consider external knowledge
    beyond dialog context for multi-turn response selection.**

1.  Three categories of Neural Ranking Models:

    1.  Representation focused models such as the DSSM model.

    2.  Interaction focused models

    3.  Combining the ideas of the representation focused models and interaction
        focused models to joint learn the lexical matching and semantic matching
        between queries and documents.

-   **The deep matching networks used in this research belongs to the
    interaction focused models.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

1.  Focusing on information-seeking conversations and building a new benchmark
    data set.

2.  Integrating external knowledge into deep neural matching networks for
    response ranking.

3.  Extensive experimental evaluation on benchmark/commercial data sets and
    promising results.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

Proposed a learning framework based on deep matching networks to leverage
external knowledge for response ranking in information-seeking conversation
systems, incorporated external knowledge into deep neural models with
pseudo-relevance feedback and QA correspondence knowledge distillation. The
methods outperform various baselines including the state-of-the-art methods.

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

Provide a method for response ranking in conversational search system, which is
one of the key problem to be solved.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Various conversational system building methods,

neural network based conversation model,

neural network based ranking model.

This research mainly focus on information oriented conversation system, and
incorporate external knowledge into deep matching network to resolve the
response ranking problem of conversational search system implement.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Implement a method to resolve response ranking in conversation systems which
incorporate external knowledge into deep matching networks.
