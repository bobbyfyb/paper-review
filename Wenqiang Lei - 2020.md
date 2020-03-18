文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Lei, W., He, X., Miao, Y., Wu, Q., Hong, R., Kan, M. Y., & Chua, T. S. (2020).
Estimation–Action–Reflection: Towards deep interaction between conversational
and recommender systems. WSDM 2020 - Proceedings of the 13th International
Conference on Web Search and Data Mining, 304–312.
https://doi.org/10.1145/3336191.3371769

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3336191.3371769?casa_token=vLCBKX5nWBsAAAAA:k8xerJ2UvOCQqzmOdJTcJ48M7t9X0yiQPC8Iluca3DthFr62KRic__J-M4znT0GFPvC9DvBUPT_B>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

There are three fundamental problems need to be solved about conversational
recommendation system:

1.  What questions to ask regarding item attributes

2.  When to recommend items

3.  How to adapt to the users’ online feedback

And in this work they fill this missing interaction framework gap by proposing a
new CRS framework .

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  The offline recommendation

>   **Such static recommendation methods suffer from the intrinsic limitation of
>   not being able to capture user dynamic preferences.**

1.  Online recommendation which target is to adapt the recommendation results
    with the user’s online actions and modeled as a multi-arm bandit problem

>   **The bandit-based solutions are still insufficient as such methods focus on
>   exploration-exploitation trade-off in cold start settings and the
>   mathematical formation of multi-arm bandit problem limits such method only
>   recommend one item each time.**

1.  Conversational recommender system

>   **Generally, prior work considers conversational recommendation only under
>   simplified settings.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Fill the missing interaction framework gap that solve the three existing
problems of conversational recommender system.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

1.  They comprehensively consider a multi-round CRS scenario that is more
    realistic than previous work, highlighting the importance of researching
    into the interactions between the RC and CC to build an effective CRS.

2.  They propose a three-stage solution, EAR, integrating and revising several
    RC and CC techniques to construct a solution that works well for the
    conversational recommendation.

3.  They build two CRS datasets by simulating user conversations to make the
    task suitable for offline academic research. They show their method
    outperforms several state-of-the-art CRS methods and provide insight on the
    task.

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

Solve the three existing problems of conversational recommender system

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Conventional recommender system

Conversational recommender system

And the insufficiency of these prior works.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose a framework that solves the three existing problems.
