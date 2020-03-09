文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Yongfeng Zhang, Xu Chen, Qingyao Ai, Liu Yang, and W. Bruce Croft. 2018. Towards
Conversational Search and Recommendation: System Ask, User Respond. In
Proceedings of the 27th ACM International Conference on Information and
Knowledge Management (CIKM ’18). Association for Computing Machinery, New York,
NY, USA, 177–186. DOI:https://doi.org/10.1145/3269206.3271776

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3269206.3271776?casa_token=uJ-pt_zjkJQAAAAA:Ap1XYE5AcDfsaCkzJJJwZqHl3Py5ycq9rGVPF5Q9wCaWrPKWuUISuV6VHVSGQ1e_P7axWfkVToba>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

1.  This research tackles the problem that there lacks a conversational search
    paradigm to integrate the search task with recent (neural) NLP techniques.

2.  This research propose to leverage large-scale user textual reviews to train
    practical conversational search models that solves the problem of lack of
    large-scale data for model training and analysis.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Basic concepts about conversational search and recommendation date back to
    some of the most early works in the community :

    1.  Croft and Thompson designed $$I^{3}R$$(Intelligent Intermediary for
        Information Retrieval) that takes activities to communicate with the
        user during a search session.

    2.  Belkin et al. designed the MERIT system that used script-based
        conversational interaction for effective search.

    3.  Radlinski and Craswell proposed a theoretical framework for
        conversational search.

    4.  Kenter and de Rijke formalized conversational search as a machine
        reading task for question answering.

    5.  Yang et al. conducted next question prediction and response ranking in
        conversations.

    6.  Spina and Trippas et al. studied the ways of presenting search results
        over speech-only channels and transcribing the spoken search recordings
        to support conversational search.

    7.  Christakopoulou et al proposed an interactive recommendation protocol
        that collects like/dislike feedback from users to refine the
        recommendations.

2.  Research about product search and recommendation:

    1.  Research about product recommendation in e-commerce.

    2.  Product search in e-commerce based on structured knowledge.

    3.  Duan et al. proposed a probabilistic mixture model by analyzing product
        search logs and proposed to extend a product database with language
        modeling to support conditional search on specifications.

    4.  Gysel et al. proposed a latent vector space model to map queries and
        products into the same latent space for product retrieval.

    5.  Ai et al. noticed that the product search task can be very personalized.

3.  Research about dialog systems and memory networks.

    1.  The partially observable Markov decision processes(POMDP-based) for
        dialog modeling.

    2.  Neural approaches to dialog systems.

    3.  Memory Networks for dialog systems, QA, language learning and machine
        reading.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose and evaluate a unified conversational search/recommendation framework in
an attempt to make the research problem doable under a standard formalization.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

1.  Proposed a system ask – user respond(SAUR) paradigm towards conversational
    search and recommendation.

2.  Based on the paradigm, proposed a multi-memory network architecture as well
    as its personalized version for conversational search and recommendation.

3.  Experiments in the Amazon e-commerce scenario based on real-world user
    purchase datasets verified the performance of the approach against
    state-of-the-art product search and recommendation baselines.

キーワードと定義
----------------

定義は自分で事典などを使って調べること 出典も明記すること

-   キーワード：定義（出典：〇〇事典）

-   キーワード：定義（本論文 p.xx）:

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

Propose a unified paradigm for conversational search and recommendation, which
can be used for further implement of conversational search systems.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Research about conversational search/recommendation, product
search/recommendation in e-commerce

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose and implement a unified framework towards conversational
search/recommendation.
