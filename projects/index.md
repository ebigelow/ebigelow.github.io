---
layout: page
title: Projects
description: Research projects I've worked on
header-img: images/projects.jpg
comments: false
modified: 2015-12-23
---





<!-- NLP
---

I'm planning to aggregate code I wrote for homeworks in statistical NLP into coherent scripts for part-of-speech tagging and machine translation (TODO...) -->



<!-- Tensor-Based Semantics for CCG
------------------------------

A project that began as the final project for my computational semantics class. TODO
 -->


Tensor Decomposition for Lifestyle Analysis
-------------------------------------------

TODO



LOTlib
------

The [language of thought hypothesis](https://en.wikipedia.org/wiki/Language_of_thought_hypothesis) asserts that humans' thoughts are composed of structures obeying the syntax of mental languages. [LOTlib](https://github.com/piantado/LOTlib) is a library allowing researchers to easily formulate compositional cognitive models as probabilistic context-free grammars (PCFGs), and then do useful things such as sampling finite-depth trees generated from an infinite grammar and computing how likely a given hypothesis (tree) would be to generate a set of human data. My primary contribution to LOTlib was working on inferring probability distributions of PCFG parameters given human data, and a pre-computed set of hypothesis trees. 







Imagistic Modeling Specialist
-----------------------------

This was the first project that I had a major part in. Beginning as a semester of independent research in "bootstrapping lexical background knowledge", I was given the task of designing a specialist system for reasoning with visual & spatial knowledge, in the spirit of existing specialist systems for reasoning with knowledge about [part, time, and color relationships](https://www.cs.rochester.edu/~schubert/papers/type-part-color-and-time-relationships83.pdf). Over the summer, two other undergraduates joined the project, which continued through the following semester. The final system produced for this task was a simple proof-of-concept which, while not useful for any real-world task, demonstrates that constructing an IMS is possible, and highlights for us a number of challenges in this construction. We published [a paper]({{ site.url }}/publications) on this in the proceedings of the [2014 Conference on Biologically Inspired Cognitive Architectures](http://bicasociety.org/meetings/2014/) at MIT, where I also gave an oral presentation.


<!-- TODO: collapsable section

Previous work to this end generally falls into one of two categories: (1) reasoning with locational knowledge, using a generic geographical model, (2) qualitative spatial reasoning (QSR), typically formalized with a [region connection calculus](https://en.wikipedia.org/wiki/Region_connection_calculus). 


The bad news is, this problem is a lot harder than we suspected when we began the IMS project. It will require a strong, efficient modeling system, which faces its a knowledge acquisition bottleneck of objects, typical properties of objects, attribute-specific predicate meanings (e.g. "The chair is *near* the sofa." vs. "Bob lives *near* Boston." vs. "Alpha Centauri is *near* our solar system."), typical scene constructions, and if we integrate time into our model, [relevant consequences of actions in the world](http://plato.stanford.edu/entries/frame-problem/).


The good news is, this problem is inversely equivalent to text-to-scene generation (see [here](http://www.cs.columbia.edu/~coyne/related-research.html) and [here](http://nlp.stanford.edu/projects/text2scene.shtml)). There is considerable common ground to be found between these tasks, as well as with human-robot interaction: all three are bottlenecked by the acquisition of the same [common-sense knowledge](https://en.wikipedia.org/wiki/Commonsense_reasoning). The "sort of good" news is that aggregating possible object relationships is not nearly as difficult a problem as aggegating possible object models, and there is a large amount of previous research on this in the QSR literature. 


I think this is a very interesting problem, and we will have to find ways to answer it sooner or later in our quest for human-like AI. When humans communicate, we paint images in each another's minds, and then we use these images to immediately infer a vast amount of knowledge. Spatial/vision common-sense knowledge is ubiquitous in human language, and some assert that [machine learning approaches will never provide solutions](https://www.cs.rochester.edu/~schubert/papers/what-kinds-of-knowledge-are-needed-for-genuine-understanding15.pdf) unless this issue is specifically targeted. Story understanding is arguably equivalent to dialogue understanding: any dialogue can be framed in the context of a story, and any story can be framed in the context of a dialogue. Patrick Winston frames these points in the context of the "Strong Story Hypothesis" and the "Directed Perception Hypothesis" (see paper [here](http://dspace.mit.edu/handle/1721.1/67693)). -->



Bloco: Miscommunication in Task-Oriented Dialogue
-------------------------------------------------

This was the first research project I worked on. It got me really excited about the structure of dialogue, and how it relates to the structue of complex actions we take in the world. The topics of [symbol grounding](https://en.wikipedia.org/wiki/Symbol_grounding_problem), [common ground](https://en.wikipedia.org/wiki/Grounding_in_communication), and [information structure in discourse](http://semanticsarchive.net/Archive/WYzOTRkO/InfoStructure.pdf) are still of great interest to me. The Bloco project now lives [here](http://personal.kent.edu/~jroche3/current-research-projects/the-bloco-project-miscommun/).

<!-- [Dialogue understanding](https://en.wikipedia.org/wiki/Dialog_system) is an [AI-hard problem](https://en.wikipedia.org/wiki/AI-complete) -- in my opinion, [the hardest](https://en.wikipedia.org/wiki/Turing_test).  -->





