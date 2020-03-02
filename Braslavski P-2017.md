文献レビューノート

書誌事項
========

学類生の場合は、SIST02形式で書誌事項を記録すること <http://inyo.nichigai.co.jp/>

Pavel Braslavski, Denis Savenkov, Eugene Agichtein, and Alina Dubatovka. 2017.
What Do You Mean Exactly? Analyzing Clarification Questions in CQA. In
Proceedings of the 2017 Conference on Conference Human Information Interaction
and Retrieval (CHIIR ’17). Association for Computing Machinery, New York, NY,
USA, 345–348. DOI:https://doi.org/10.1145/3020165.3022149

PDFのURL
========

オンライン上で見つけた場合

<https://dl.acm.org/doi/pdf/10.1145/3020165.3022149?casa_token=obVei0oayyYAAAAA:_OgiE1My1fqcaa3_Dhl7M19SSeHc6xiss8CcQR2b3T6ldSHkxigN5p6awqf2gfJ44d-SozFEonhO>

序論の3戦略
===========

以下の3戦略は論文に明記されているとは限らない
背景情報を調べる（読み取る）必要があるかもしれない

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

-   Many experts envision that search in the near future will be a dialog
    between a user and an intelligent assistant, rather than just “ten blue
    links” in response to a one-hot keyword query.

-   One key capability required to make search dialogues effective is asking
    clarification questions(CLARQ) proactively, when a user’s intent is not
    clear, which could help the system provide more useful responses.

-   Finds of the research can be useful for future improvements of intelligent
    dialog search and question answering systems.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

-   Kotov and Zhai introduced a concept of question-guided search, which can be
    seen as a variant of query suggestion scenario: in response to initial query
    the user is presented with a list of natural language questions that reflect
    possible aspects of the information need behind the query.

-   Tang et al. proposed a method for refinement question generation based on
    similar questions retrieved from a question archive, a thesaurus and
    question templates.

-   Sajjad et al. described a framework for search over a collection of items
    with textual descriptions exemplified with xbox avatar assets.

**Researches above demonstrate successful cases of CLARQ for search tasks. This
research looks into uses of CLARQ in answer seeking dialogs between real users,
which could be useful for future improvements of the systems.**

-   Kato et al. investigated clarification questions in context of an enterprise
    Q&A instant messaging in software domain, in which has shown that about one
    third of all dialogues have clarification requests, and 8.2% of all
    utterances in the log are related to clarifications.

**The work above is closed to this research that they both analyze human Q&A
behavior, however, this research deal with a different type of data – QA
archives – and investigate if the resource can be potentially useful for a
different application – QA .**

-   Anderson et al. showed that long-term value of a question and its answers on
    Stack Overflow was positively correlated with the number of comments on the
    answers and the time for highest-score answer to arrive.

**This research complements these studies and focus on clarification comments to
gather insights, useful for automatic conversational search system
development.**

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

-   To learn about user behavior associated with CLARQ and about their role in
    CQA communications.

-   To study the types of CLARQ users asks in different situations.

-   To make the first step towards automatic generation of CLARQ: build a model
    to predict the subject of a particular popular type of clarification
    questions.

主な結果と考察
--------------

本論文で得られた主な結果とその結果が意味することは何か

-   Based on their analyses, they conclude that CLARQ are common in CQA
    archives, and introduce a valuable resource for user behavior studies and QA
    research.

-   They see that clarification questions are quite diverse in topic and style,
    and are highly dependent on context and individual characteristics of the
    users. However, there are several types of questions and syntactic patterns
    that are common within each domain.

-   Their experiment show promising results on identifying the subject of CLARQ
    based on a small set of shallow features.

-   Their findings suggest that CQA data may be useful for research in the field
    of interactive QA.

キーワードと定義
----------------

定義は自分で事典などを使って調べること 出典も明記すること

-   キーワード：定義（出典：〇〇事典）

-   キーワード：定義（本論文 p.xx）

-   Clarification question: questions that makes something clear or easier to
    understand. (from Cambridge dictionary)

-   CQA – communicate question answering website: websites that allow users to
    post questions on various topics to other community members, vote for
    questions and answers, as well as gain scores for their activities, such as
    Yahoo!Answers, Quora, and Stack Exchange.(from this paper p.345).

その他気づいたこと
------------------

Future works suggested by this research:

The use of candidate answers.

The use of domain-specific knowledge-based approach to CLARQ generation.

自分の3戦略
===========

今回レビューした論文をお手本にして新しい論文を書くと仮定すると
どのような3戦略が考えられるか

戦略1：研究領域の確立
---------------------

この研究テーマは社会的にどのような重要性があるのか
重要性を示唆する統計情報はあるか

The ability to ask suitable clarification questions and to decide when to ask
clarification questions is of great important when implement conversational
search assistant.

戦略2：先行研究の隙間
---------------------

重要なテーマについて過去の研究者はどのような研究を行ってきたのか
既存研究にはどのような隙間（限界）があるのか
または、どのような新しい研究機会が考えられるのか

The use of clarification questions in search tasks, the analysis of human QA
behavior, and the importance of the ability to ask clarification questions for
conversational search system implement has been proposed by the related works,
while the analysis about clarification questions in the COA archives has not
been researched.

戦略3：研究の目的
-----------------

本論文の具体的な研究目的は何か

To analysis the effect and importance of clarification questions in CQA
archives, that proves the importance of clarification questions for
conversational search system implement.
