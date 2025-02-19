Research
========

I am an assistant professor at Uppsala University, working on
programming languages, semantics and type systems. I am currently
involved in the following projects:.

- [Verona](https://www.microsoft.com/en-us/research/project/project-verona/),
  a new programming language for infrastructure programming,
  featuring a novel concurrency model called [behaviour-oriented
  concurrency](https://uu.diva-portal.org/smash/get/diva2:1791738/FULLTEXT01.pdf)
  with a co-designed [type
  system](http://www.diva-portal.org/smash/get/diva2:1791730/FULLTEXT01.pdf).
- [Trieste](https://github.com/microsoft/Trieste), a DSL for
  [experimental development](papers/sle24.pdf) of multi-pass
  compilers, featuring built-in support for property-based
  testing.
- [Miking](https://miking.org/), a framework for rapid development
  of domain-specific languages based on [composition of language
  fragments](https://people.kth.se/~dbro/papers/broman-2019-miking-vision.pdf),
  featuring parsing with [statically resolvable
  ambiguity](https://dl.acm.org/doi/10.1145/3571251).

I used to be a post-doc researcher in [David
Broman](https://www.kth.se/profile/dbro){:target="blank"}'s
[group](https://www.kth.se/scs/mcs){:target="blank"} at
[KTH](http://www.kth.se){:target="blank"}, working on
[heterogeneous model compilers and
semantics](https://people.kth.se/~dbro/hmc.html){:target="blank"},
as well as [full-stack verification of programs synthesized from
timed automata](https://people.kth.se/~dbro/projects.html){:target="blank"}.

I did my PhD with [Tobias
Wrigstad](http://www.wrigstad.com){:target="blank"} and [Dave
Clarke](http://supercooldave.github.io/){:target="blank"} at
[Uppsala University](http://www.it.uu.se){:target="blank"}. There,
I did research on type systems for controlling aliasing and
preventing data-races in concurrent and parallel programs.

In 2018, I did an internship at Microsoft Research in Cambridge,
working together with [Matthew
Parkinson](https://www.microsoft.com/en-us/research/people/mattpark/){:target="blank"}
and [David
Chisnall](https://www.cl.cam.ac.uk/~dc552/){:target="blank"} on
compiler-based mitigation of the
[Spectre](https://meltdownattack.com/) attacks.

I was one of the main contributors to
[Encore](https://encore-lang.github.io/){:target="blank"}, a
highly concurrent object-oriented programming language. Encore's
type system guarantees the absence of data-races and is based on
my work on
[Kappa](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-336021){:target="blank"}.

I am always interested in discussing collaboration!

[](TODO: List co-authors for publications)

Publications and Presentations
------------------------------
* [2024] Trieste: A C++ DSL for Flexible Tree Rewriting -- SLE'24 ([paper](papers/sle24.pdf))
* [2024] Arrays in Practice: An Empirical Study of Array Access
  Patterns on the JVM -- Programming'24 ([paper](https://programming-journal.org/2024/8/14/))
* [2023] Reference Capabilities for Flexible Memory Management -- OOPSLA'23
  ([paper](https://dl.acm.org/doi/10.1145/3622846))
* [2023] Encore: Coda -- Springer Nature (Paper to be posted)
* [2023] Statically Resolvable Ambiguity -- POPL'23
  ([paper](https://dl.acm.org/doi/10.1145/3571251)|[artifact](https://zenodo.org/record/7260815))
* [2021] Resolvable Ambiguity: Principled Resolution of
  Syntactically Ambiguous Programs -- CC'21
  ([paper](https://dl.acm.org/doi/abs/10.1145/3446804.3446846?casa_token=0jwoP6VMYywAAAAA:B05qIyoBYP-80vRFKWZ2ucdYQ0zSwVkhEw6te17p4cC5Wrla9k2XGcdxCAdLCUG2bggHZcERwnmQ))
* [2020] Reference Capabilities for Safe Parallel Array
  Programming -- Programming'20 ([paper](https://programming-journal.org/2020/4/1/))
* [2019] Developing a Monadic Type Checker for an Object-Oriented
  Language: An Experience Report -- SLE'19 (Distinguished Artifact Award)
  ([preprint](papers/sle19.pdf)|[artifact](https://github.com/parapluu/monadic-typechecker){:target="blank"})
* [2019] Progress Report: Exploring API Design for Capabilities
    for Programming with Arrays -- ICOOOLPS'19 ([paper](http://kth.diva-portal.org/smash/record.jsf?dswid=-481&faces-redirect=true&language=en&searchType=SIMPLE&query=&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&pid=diva2%3A1349621%22&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=all))
* [2018] OOlong: a concurrent object calculus for extensibility
  and reuse -- ACM SIGAPP ([paper](papers/oolong.pdf) |
  [artifact](https://github.com/EliasC/oolong))
* [2018] Attached and Detached Closures in Actors --
  AGERE@SPLASH'18 ([paper](papers/agere18.pdf) | [slides](slides/agere18.pdf))
* [2018] Cflat: A New Modular Approach to Implementing Efficient
  and Tunable Collections -- Onward!
  ([paper](http://stbr.me/cflat))
* [2018] Bestow and Atomic: Concurrent Programming using
  Isolation, Delegation and Grouping -- JLAMP
  ([paper](https://authors.elsevier.com/a/1XKyV8MrKMFw0Q))
* [2018] Parallel programming with arrays in Kappa --
  ARRAY@PLDI'18
  ([paper](https://dl.acm.org/citation.cfm?id=3219757))
* [2018] Forward to a Promising Future -- COORDINATION'18 (Best Paper Award)
  ([paper](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1209721&dswid=-2080))
* [2018] Capability-Based Type Systems for Concurrency Control -- PhD Thesis
  ([extensive summary](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-336021))
* [2017] OOlong: An Extensible Concurrent Object Calculus -- OOPPS@SAC'17
  ([preprint](papers/sac18.pdf) | [slides](slides/SAC18.pdf) | [artifact](https://github.com/EliasC/oolong))
* [2017] Reference Capabilities for Concurrency & Scalability: an Experience Report -- OCAP'17
  ([slides](slides/OCAP17.pdf) | video forthcoming)
* [2017] Mastery Learning-Like Teaching with Achievements -- SPLASH-E'17
  ([paper](https://2017.splashcon.org/event/splash-2017-splash-e-cer-mastery-learning-like-teaching-with-achievements))
* [2017] Relaxed Linear References for Lock-Free Data Structures -- ECOOP'17
  ([paper and talk](http://2017.ecoop.org/event/ecoop-2017-papers-relaxed-linear-references-for-lock-free-programming){:target="blank"} | [slides](slides/ECOOP17.pdf){:target="blank"})
* [2017] Actors without Borders: Amnesty for Imprisoned State -- PLACES'17
  ([paper](https://arxiv.org/abs/1704.03094){:target="blank"} | [slides](slides/ActorsWithoutBorders.pdf){:target="blank"})
* [2016] Reference Capabilities for Trait Based Reuse and Concurrency Control -- Technical Report
  ([paper](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-309774){:target="blank"})
* [2016] Types for CAS: Relaxed Linearity with Ownership Transfer -- NWPT'16
  ([paper](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-309777){:target="blank"})
* [2016] LOLCAT: Relaxed Linear References for Lock-free Programming -- Technical Report
  ([paper](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-309776){:target="blank"})
* [2016] Reference Capabilities for Concurrency Control -- ECOOP'16
  ([paper and talk](http://2016.ecoop.org/event/ecoop-2016-papers-reference-capabilities-for-concurrency-control){:target="blank"} | [slides](slides/ECOOP16.pdf){:target="blank"} | [poster](posters/ECOOP16.pdf){:target="blank"})
* [2016] Kappa: Insights, Current Status and Future Work -- IWACO'16
  ([paper](http://2016.ecoop.org/event/iwaco-2016-first-paper-kappa-insights-current-status-and-future-work){:target="blank"} | [slides](slides/IWACO16.pdf){:target="blank"})
* [2015] Refined Ownership: Fine-grained controlled internal sharing -- SFM'15
  ([paper](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-266673){:target="blank"})
* [2015] Parallel Objects for Multicores: A Glimpse at the Parallel Language Encore -- SFM'15
  ([paper](https://www.it.uu.se/katalog/stebr742/Encore-Glimpse/Encore_Glimpse_Preprint.pdf){:target="blank"})
* [2014] Capable: Capabilities for Scalability -- IWACO'14
  ([paper](http://www.ownership-types.org/iwaco14/program_files/Paper2.pdf){:target="blank"} | [slides](slides/IWACO14.pdf){:target="blank"})


Community Service
-----------------
* [2025] [MoreVMs'25](https://2025.programming-conference.org/home/MoreVMs-2025), reviewing
* [2025] [GulFest](https://2025.programming-conference.org/home/MoreVMs-2025), reviewing
* [2024] [JLAMP](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming), reviewing
* [2024] [TCPS](https://dl.acm.org/journal/tcps), reviewing
* [2024] [SLE'24](https://2024.splashcon.org/track/sle-2024), program committee
* [2024] [IWACO'24](https://2024.splashcon.org/home/iwaco-2024), program committee
* [2023] [ICOOOLPS'23](https://2023.issta.org/track/ICOOOLPS-2023), program committee
* [2023] [VIMPL'23](https://2023.programming-conference.org/home/vimpl-2023), program committee
* [2023] [IWACO'23](https://2023.splashcon.org/home/iwaco-2023), program committee
* [2023] [PLACES'23](https://places-workshop.github.io/2023/), program committee
* [2022] [SCP](https://www.sciencedirect.com/journal/science-of-computer-programming), reviewing
* [2021] [SPLASH'21](https://2021.splashcon.org/track/splash-2021-SRC){:target="blank"}, student research competition judge
* [2021] [SLE'21](https://conf.researchr.org/home/sle-2021){:target="blank"}, artifact evaluation co-chair
* [2021] [AGERE'21](https://2021.splashcon.org/home/agere-2021){:target="blank"}, member of the organizing committee.
* [2020] [AGERE'20](https://2020.splashcon.org/home/agere-2020){:target="blank"}, member of the organizing committee.
* [2020] [OOPSLA'20 Artifact Evaluation Committee](https://2020.splashcon.org/track/splash-2020-Artifacts){:target="blank"}.
* [2020] [PLDI'21 Artifact Evaluation Committee](https://pldi20.sigplan.org/track/pldi-2020-PLDI-Research-Artifacts){:target="blank"}.
* [2019] [AGERE'19](https://2019.splashcon.org/home/agere-2019){:target="blank"}, member of the organizing committee.
* [2019] [LCTES'19 Artifact Evaluation Committee](https://conf.researchr.org/committee/LCTES-2019/lctes-2019-papers-artifact-evaluation-committee){:target="blank"}
* [2019] [PLDI'19 Artifact Evaluation Committee](https://pldi19.sigplan.org/track/pldi-2019-PLDI-Research-Artifacts){:target="blank"}
* [2018]
  [ECOOP'18 Artifact Evaluation Committee](http://2018.ecoop.org/track/ecoop-2018-Artifacts){:target="blank"}
* [2018]
  [PLDI'18 Artifact Evaluation Committee](https://pldi18.sigplan.org/track/pldi-2018-PLDI-Research-Artifacts){:target="blank"}
* [2017]
  [OOPSLA'17 Artifact Evaluation Committee](http://2017.splashcon.org/track/splash-2017-OOPSLA-Artifacts){:target="blank"}
* [2017]
  [IWACO'17](2017.ecoop.org/track/iwaco-2017-papers){:target="blank"}, co-chair and
  organizer together with [Juliana Franco](https://www.doc.ic.ac.uk/~jvicent1/){:target="blank"}.
* [2017]
  [ECOOP'17 Artifact Evaluation Committee](http://2017.ecoop.org/track/ecoop-2017-Artifacts){:target="blank"}
* [2017]
  Subreviewing for ECOOP and OOPSLA
* [2016]
  [OOPSLA'16 Artifact Evaluation Committee](http://2016.splashcon.org/track/splash-2016-artifacts){:target="blank"}
* [2016]
  Subreviewing for ECOOP and OOPSLA
* [2015]
  Subreviewing for PLDI, ECOOP, OOPSLA, CONCUR and SAC
* [2014] ECOOP'14, local student aid


Teaching
========

Since 2021 I am the main teacher of a second year 20 ECTS credits
course at Uppsala University called Imperative and Object-Oriented
Programming Methodology (or IOOPM for short). In 2021 I was the
proud recipient of the Union of Engineering and Science Student's
Teaching Award!

Since 2023 I also teach a 5 ECTS credit course on Programming
Language Semantics.

Previous courses taught include:

* Computer Hardware Engineering (7.5 ECTS, KTH), 2019
* Program Design and Data Structures (20 ECTS, UU), 2016-2017
* Imperative and Object-Oriented Programming Methodology (20 ECTS,
  UU), 2012-2018


Students
--------

I am the main supervisor of the following PhD students:

* Matilda Blomqvist (since 2023)

I have co-supervised the following PhD students:

* Ellen Arvidsson (since 2021)
* Viktor Palmkvist (since 2021, graduated 2024)
* Beatrice Åkerblom (since 2019, graduating in 2025)

I am currently supervising the following bachelor thesis projects:

* Emma Angetun -- Extending the Object Calculus OOlong
* Linus Waehler -- Can ChatGPT Achieve Mastery? Using ChatCPT to Pass a Second Year University Programming Course

I have supervised the following master thesis projects:

* Alfrida Mattisson -- Automatically Choosing Implementations of Abstract Data Types

I have supervised the following bachelor thesis projects:

* Gustav Lundin -- [Pattern Matching in Encore](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-294513){:target="blank"}
* Christian Törnqvist -- [Finding Patterns in Lock-Free Algorithms](http://uu.diva-portal.org/smash/record.jsf?pid=diva2:1136791)
* Joel Wallin -- [Implementing Safe Sharing Features in Encore](theses/thesis-joelwallin.pdf)
* Jonas Olander -- [Separate Compiling for Encore](http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-330697)
* Tage Johansson -- [A Strongly Typed Shell with Full Control over Side Effects](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1864006&dswid=-4984)
* Victor Odebäck -- [CTriPio: Developing an Intermediate Representation of C code in Trieste for Static Analysis](http://uu.diva-portal.org/smash/record.jsf?pid=diva2%3A1891513&dswid=-9888)

Personal
========

I spend a lot of my free time on listening to and creating music.

* From 2008 to 2017 I was the conductor of
  [Kalmar Nation's Choir](http://kalmarnation.se/koren){:target="blank"}
  in Uppsala.
  [Here](https://www.youtube.com/watch?v=cgrlqO8PqJs){:target="blank"}
  is a video of us performing of Vienna Teng's beautiful Hymn of Acxiom.
* Since 2015 I am a singer in
  [Uppsala Vokalensemble](http://uppsalavokalensemble.se/){:target="blank"}.
* I also like to write and arrange choir music.
  [Here](https://www.youtube.com/watch?v=L0ut0ADUdp8) is a
  recording of my arrangement of the traditional Swedish hymn "Den
  blomstertid nu kommer". You can also [buy the arrangement](https://www.gehrmans.se/butik/kor/blomstertid-13893)!
  [Here](https://www.youtube.com/watch?v=l2gzhjwBczI){:target="blank"}
  is a recording of my setting of Alfred Tennyson's Now Sleeps the
  Crimson Petal, performed by the women's choir
  [Discordia](http://udkdiscordia.se/){:target="blank"}. [](TODO: Another page)
* I play the electric and upright
  bass. [Here](https://www.youtube.com/watch?v=VPzk-28ZiYc) is a
  recording I made as a Christmas present for the friend who
  introduced me to the wonderful music of [Vulfpeck](http://vulfpeck.com/){:target="blank"}.
* I play bass in the now dormant band Morfis. Our album
  [Dunia](https://open.spotify.com/album/0Sn5iIamcssFcc6EdZvnzi){:target="blank"}
  from 2013 is on Spotify! I wrote and arranged the songs Gånglåt
  från Gottsunda ("Walking Song from Gottsunda"), Cykeltjuven
  ("The Bicycle Thief") and Kometen ("The Comet").