文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Mohammad Aliannejadi, Hamed Zamani, Fabio Crestani, and W. Bruce Croft. 2019.
Asking Clarifying Questions in Open-Domain Information-Seeking Conversations. In
Proceedings of the 42nd International ACM SIGIR Conference on Research and
Development in Information Retrieval (SIGIR’19). Association for Computing
Machinery, New York, NY, USA, 475–484.
DOI:https://doi.org/10.1145/3331184.3331265

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3331184.3331265?casa_token=NMFgI7rRkxQAAAAA:eLGqL6wNPEUdnI_CD92jI_Da7NYld0Nr3c8p_U6KgB7tHLtUfm_FzkgT7qPlmD5hQ9pbaE3cZSCb>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

While searching on the Web, user often fail to formulate their complex
information needs in a single query. As a consequence, they may need to scan
multiple result pages or reformulate their queries,

Therefore, asking clarifying questions is especially important in conversational
systems since they can only return a limited number of (often only one)
result(s).

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Research about Conversational IR

2.  Research about question suggestion.

3.  Research about clarifying question.

>   **These researches set the fundamental of this paper.**

1.  Research about interacting with users for recommendation.

>   **This paper’s work is distinguished from these studies by formulating the
>   problem of asking clarifying questions in an open-domain information-seeking
>   conversational setting where several challenges regarding extracting topic
>   facets are different from a recommendation setting.**

1.  Research about question ranking and generation.

>   **This paper studies the task of asking clarification question in an IR
>   setting where the user’s request is in the form of short queries (vs. a long
>   detailed post on StackOverflow) and the system should return a ranked list
>   of documents.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Formulate the task of selecting and asking clarifying questions in open-domain
information-seeking conversational system.

Propose an offline evaluation framework based on faceted and ambiguous queries
and collect a novel dataset.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

The analysis of the oracle model provides important intuitions related to this
task.

Proposed a retrieval framework consisting of three main components as follows:
(i) question retrieval; (ii) question selection; (iii) document retrieval, which
significantly outperforms the baseline of competitive term-matching and learning
to rank models.

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

In a conversational information-seeking setting, users often cannot formulate
their information needs properly into a single query, and often need a
multi-turn back-and-forth interaction between the users and system to clarify
their information needs. Because of this system can proactively asks clarifying
questions to clarify the user’s intent thus satisfying the users.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Research about Conversational IR, clarifying questions, question generation and
selection.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Formulate the task of asking clarifying questions and propose a framework to
implement this ability.
