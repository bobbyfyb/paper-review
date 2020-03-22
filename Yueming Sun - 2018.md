文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Sun, Y., & Zhang, Y. (2018). Conversational recommender system. 41st
International ACM SIGIR Conference on Research and Development in Information
Retrieval, SIGIR 2018, 235–244. <https://doi.org/10.1145/3209978.3210002>

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3209978.3210002?casa_token=FeW5YYeGSIIAAAAA:wKE-0WL4tDPANvScyIjqG-NVQAarSXYR1z5GuTdJoj8I_aUeRB9wxwOSYktjGOrr--EOYsrgOL3W>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

A personalized conversational sales agent could have much commercial potential.

Research about conversational recommender system can benefit both recommender
systems and dialog systems.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Dialogue system.

**Most of those prior works focus on NLP challenges instead of commercial
success metrics such as conversion rate. They either did not focus on
recommendation problems or did not model or utilize the users’ past preferences
when recommending items to users.**

Recommender systems

**Few works have been done towards making recommendations in a dialogue system.
This research maximizes the long-term utility by using the reinforcement
learning framework, and their question types are requesting facets from users
and recommending a list of items to users, which are better aligned with the
typical dialogue systems.**

Facet search

**This research introduces a particular type of machine actions into their
conversational system: selecting a facet based on the context and asking user to
provide information about her preferred facet value by reinforcement learning
algorithm.**

Deep reinforcement learning.

**Deep RL has been applied for better sequential decision making in various
domains. This research builds a deep RL based conversational recommendation
system, which combines the ranking and personalization ability for recommender
system with the sequential decision-making power of the RL models, thus can
better serve a user.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

To integrate research in dialog systems and recommender systems into a novel and
unified deep reinforcement learning framework to build a personalized
conversational recommendation agent that optimizes a per session-based utility
function.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

Proposed a unified framework to integrate recommender systems and dialogue
system technologies together for building an intelligent conversational
recommender system

Introduced the reward function for the conversational system based on the
recommendation systems research.

Developed a demo system. Both the online and offline evaluation results
demonstrate the merits of introducing recommendation techniques into a
reinforcement learning based conversational system.

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

Propose a framework that combines both the advantage of recommendation system
and dialog system that can better satisfying users’ information need.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Research about dialog system, recommendation system, deep RL.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Propose a unified framework of conversational recommendation system.
