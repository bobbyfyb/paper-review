文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Exploration, A., Author, D. A. A., & Id, S. (2020). Conversations with
Documents. *CHIIR 2020 - Proceedings of the 2020 Conference on Human Information
Interaction and Retrieval*, 43–52.

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/abs/10.1145/3343413.3377971>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

It has the potential to tremendously increase a user’s productivity while has
seen less significant progress.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

1.  Voice-controlled document narration

    1.  Vtyurina et al. developed VERSE, a system that adds screen reader-like
        capabilities into a more contemporary virtual assistant, which
        meaningfully extended the capabilities of virtual assistants, but that
        the QA and document navigation capabilities were too disjoint –
        participants expressed a strong interest in being able to ask questions
        about the retrieved documents. This strongly motivates the research
        presented in this paper.

2.  Interactions with productivity software. Fourney and Dumais investigate
    different types of queries users pose to a conversational assistant, and
    they show that different types of queries can be reliably detected and that
    forms of query alteration can boost retrieval performance.

3.  Question Answering.

    1.  A lot of progress has been made in the area, driven by the successful
        application of deep learning architectures and the increase of
        large-scale datasets. In addition, none of them contain queries that
        reference the document directly as the subject of the query, a
        distinction that can cause existing QA models to yield irrelevant or
        confusing responses.

    2.  Targeted neural QA, pretrained language representation model BERT which
        can be fine-tuned on a specific task by adding an additional output
        layer. This paper bases the baseline models on BERT transformers.

    3.  QA work that focus on low resource setting which are also this paper’s
        interests.

With the possible exception of VERSE, none have specifically explored how people
might want to receive conversation-based assistance with documents, and in
particular documents that they have rich context about.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Research focusing on document-centered assistance. Investigate this space of
document-centered assistance, specifically focus on text consumption and
document comprehension scenarios in a work context.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

1.  Present a survey to understand the space of document-centered assistance and
    the capabilities people expect in this scenario.

2.  Investigate the types of queries that user will pose while seeking
    assistance with documents, and show that document-centered questions from
    the majority of these queries.

3.  Present a set of initial machine learned models that show that a) they can
    accurately detect document-centered questions, b) they can build reasonably
    accurate models for answering such questions.

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

Give an insight into intelligent assistant that help people with assistance
about documents which can increase their productivity.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

Voice-based interface about document, QA system

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

Research about the conversation where user seeks for assistance about
interacting with document, and conduct experiments that try to construct such
intelligent assistant.
