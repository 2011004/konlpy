References
==========

.. role:: license

.. role:: language

.. note::
    Please `modify this document <https://github.com/konlpy/konlpy/blob/master/docs/references.rst>`_ if anything is erroneous or not included.
    Last updated at |today|.

.. _engines:

Korean morpheme analyzer tools
------------------------------

When you're analyzing Korean text, the most basic task you need to perform is morphological analysis.
There are several libraries in various programming languages to achieve this:

C/C++
'''''
- `KTS <http://wiki.kldp.org/wiki.php/KTS>`_ (1995) :license:`GPL v2`
    - By 이상호, 서정연*, 오영환 (KAIST & Seogang University)
    - `code <http://kldp.net/projects/kts/src>`_
- `MACH <http://cs.sungshin.ac.kr/~shim/demo/mach.html>`_ (2002) :license:`custom`
    - By Kwangseob Shim* (성신여대)
    - Kwangseob Shim, Jaehyung Yang, `MACH: A Supersonic Korean Morphological Analyzer <http://www.aclweb.org/anthology/C02-1092>`_, ACL, 2002.
- `MeCab-ko <https://bitbucket.org/eunjeon/mecab-ko/>`_ (2013) :license:`GPL` :license:`LGPL` :license:`BSD`
    - By Yong-woon Lee and Youngho Yoo

Go
''

- `go_hangul <https://github.com/suapapa/go_hangul>`_ (2012) :license:`BSD`

Java/Scala
''''''''''

- `twitter-korean-text <https://github.com/twitter/twitter-korean-text/>`_ (2014) :license:`Apache v2`
    - By Will Hohyon Ryu (Twitter)
- `KOMORAN <http://shineware.tistory.com/tag/KOMORAN>`_ (2013) :license:`Apache v2`
    - By *shineware*
- `KKMA <http://kkma.snu.ac.kr>`_ (2010) :license:`GPL v2`
    - By Sang-goo Lee* et al. (Seoul National University)
    - Generates morpheme candidates using dynamic programming
    - Tags morphemes by checking neighbors, and employing some heuristics and HMM models
    - Developer blog: `Dongjoo Lee <http://therocks.tistory.com>`_
- `Arirang <http://cafe.naver.com/korlucene>`_ (2009) :license:`Apache v2`
    - By SooMyung Lee
    - `code <http://sourceforge.net/projects/lucenekorean>`_
- `Hannanum <http://semanticweb.kaist.ac.kr/home/index.php/HanNanum>`_ (1999) :license:`GPL v3`
    - By Key-Sun Choi* et al. (KAIST)
    - `code <http://kldp.net/projects/hannanum/src>`_, `docs <http://semanticweb.kaist.ac.kr/research/hannanum/j/javadoc/>`_

Python
''''''

- `KoNLPy <http://konlpy.org>`_ (2014) :license:`GPL v3`
    - By Lucy Park (Seoul National University)
- `UMorpheme <https://pypi.python.org/pypi/UMorpheme>`_ (2014) :license:`MIT`
    - By Kyunghoon Kim (UNIST)

R
''

- `KoNLP <https://github.com/haven-jeon/KoNLP>`_ (2011) :license:`GPL v3`
    - By Heewon Jeon

Others
''''''

- `K-LIWC <http://k-liwc.ajou.ac.kr/>`_ (아주대)
- `KRISTAL-IRMS <http://www.kristalinfo.com/>`_ (KISTI)
    - `Development history <http://spasis.egloos.com/9507>`_
- `Korean XTAG <http://www.cis.upenn.edu/~xtag/koreantag/>`_ (UPenn)
- `HAM <http://nlp.kookmin.ac.kr/HAM/kor/ham-intr.html>`_ (국민대)
- `POSTAG/K <http://nlp.postech.ac.kr/~project/DownLoad/k_api.html>`_ (POSTECH)
- `Speller <http://speller.cs.pusan.ac.kr/>`_ (부산대)
- `UTagger <http://203.250.77.242:5900/>`_ (울산대)
- `(No name) <http://cl.korea.ac.kr/Demo/dglee/index.html>`_ (Korea University)


Other NLP tools
---------------

- `Hangulize <http://www.hangulize.org/>`_ - By Heungsub Lee :language:`Python`
    - Hangul transcription tool to 38+ languages
- `Hanja <https://github.com/suminb/hanja>`_ - By Sumin Byeon :language:`Python`
    - Hanja to hangul transcriptor
- `Jamo <http://github.com/JDong820/python-jamo>`_ - By Joshua Dong :language:`Python`
    - Hangul syllable decomposition and synthesis
- `KoreanParser <http://semanticweb.kaist.ac.kr/home/index.php/KoreanParser>`_ - By DongHyun Choi, Jungyeul Park, Key-Sun Choi (KAIST) :language:`Java`
    - Language parser
- `Korean <http://pythonhosted.org/korean>`_ - By Heungsub Lee :language:`Python`
    - Package for attaching particles (josa) in sentences
- `BoRA 언어자원은행 <http://semanticweb.kaist.ac.kr/org/bora/>`_ - By KAIST

.. _corpora:

Corpora
-------

- Yonsei Corpus, 연세대, 1987.
    - 42M tokens of Korean since the 1960s
- Korea University Korean Corpus, 1995.
    - 10M tokens of Korean of 1970-90s
- `HANTEC 2.0 <http://www.kristalinfo.com/download/#hantec>`_, KISTI & 충남대, 1998-2003.
    - 120,000 test documents (237MB)
    - 50 TREC-type questions for QA (48KB)
- `HKIB-40075 <http://www.kristalinfo.com/TestCollections/readme_hkib.html>`_, KISTI & 한국일보, 2002.
    - 40,075 test documents for text categorization (88MB)
- `KAIST Corpus <http://semanticweb.kaist.ac.kr/home/index.php/KAIST_Corpus>`_, KAIST, 1997-2005.
- `Sejong Corpus <http://www.sejong.or.kr/>`_, National Institute of the Korean Language, 1998-2007.

General NLP resources
---------------------

- `Google NLP publications <http://research.google.com/pubs/NaturalLanguageProcessing.html>`_
- `Lingpipe <http://alias-i.com/lingpipe/>`_
- `Microsoft NLP group (Redmond) <http://research.microsoft.com/en-us/groups/nlp/>`_
- `부산대 NLP 관련사이트 목록 <http://borame.cs.pusan.ac.kr/ai_home/site/site1.html>`_
- `Sejong semantic search system <http://sejong21.org>`_
- `한글 및 한국어 정보처리 학술대회 <http://sites.google.com/site/sighclt/gongjisahang>`_
