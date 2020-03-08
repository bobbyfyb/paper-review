文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Chen Qu, Liu Yang, W. Bruce Croft, Johanne R. Trippas, Yongfeng Zhang, and
Minghui Qiu. 2018. Analyzing and Characterizing User Intent in
Information-seeking Conversations. In The 41st International ACM SIGIR
Conference on Research & Development in Information Retrieval (SIGIR ’18).
Association for Computing Machinery, New York, NY, USA, 989–992.
DOI:https://doi.org/10.1145/3209978.3210124

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3209978.3210124?casa_token=WD9-3C-XjoIAAAAA:vHRBgeIHtd-4frECnB1iNJZPDp56KOn9YWdOpdfT9ek3XAYUqIYGbIFvj-w0ZvQuP203uyGgnhmn>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

This research introduced a new dataset designed for understanding and
characterizing how people interact in information-seeking conversations which is
crucial in developing conversational search systems, which should be a first
step to analyze and predict user intent in an information-seeking setting.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  The Ubuntu Dialog Corpus(UDC) dataset which contains multi-turn QA
    conversations in the technical support domain.

>   **This dataset is unlabeled and the dialogs of it are in IRC(Internet Relay
>   Chat) style, in which contains a significant amount of typos, internet
>   language, and abbreviations.**

1.  The DSTC 6 Conversation Modeling track data which contains knowledge
    grounded dialogs from Twitter.

>   **This dataset contains scenarios where users do not request information
>   explicitly, which do not fit the information-seeking narrative.**

1.  Early conversational search systems through man-machine dialog THOMAS system
    that introduced by Oddy, which allowed users to conduct searches through
    dialogs.

2.  Belkin et al. explored and demonstrated the justifiability of using
    information interaction dialogs to design the interaction mechanisms in IR
    system.

3.  Shah and Pomerantz considered community QA as information-seeking process
    and built models to predict answer quality.

4.  Radlinski and Craswell described a conceptual framework for conversational
    IR and the major research issues that must be addressed.

5.  Trippas et al. analyzed the initial turns for patterns to classify with a
    qualitative analysis approach.

6.  The MISC data which came from similar experiments with data release
    including video, audio, and even emotions.

>   **Even they offered valuable insights no how users conduct searches in a
>   conversation, the data is not sufficient to perform a large-scale analysis
>   and model training.**

1.  Marchionini and White and Roth addressed the importance of exploratory
    search, where the behavior if search is beyond a simple look up and more
    like learning and investigating.

>   **This highlights the research need to characterize and understand user
>   intent dynamics in information-seeking processes.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

1.  Create a large-scale annotated dateset for multi-turn information-seeking
    conversations.

2.  Perform in-depth data analysis and characterization of multi-turn human QA
    conversations.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

1.  Created the MSDialog dataset. Although this dataset does not cover every
    aspect of the highly diverse information-seeking conversations, it should be
    a first step to analyze and predict user intent in an information-seeking
    setting.

2.  Performed in-depth characterization and analysis of this data to gain
    insights on the distribution, co-occurrence and flow pattern of user intent
    in information-seeking conversations. The patterns discovered are closely
    related to several design choices, including using dialogs from a well
    moderated forum in a specific domain.

キーワードと定義
----------------

定義は自分で事典などを使って調べること 出典も明記すること

-   キーワード：定義（出典：〇〇事典）

-   キーワード：定義（本論文 p.xx）

User intent: User intent, otherwise known as query intent or search intent, is
the identification and categorisation of what a user online intended or wanted
to find when they typed their search terms into an online web search engine for
the purpose of search engine optimisation or conversion rate optimization (from
Wikipedia)

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

Introduce a dataset for understanding and analyzing user interaction in
information-seeking conversation and perform analysis on it, which can encourage
further exploration of information-seeking conversation models.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Existing dataset for conversational information-seeking interactions and the
deficiencies of them.

Research about user intent and its importance in conversational
information-seeking process.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Introduce a new dataset which aims to user interaction behavior in
conversational information-seeking interaction.

Perform analysis about user intent using the dataset proposed.
