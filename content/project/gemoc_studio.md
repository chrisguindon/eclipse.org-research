---
title: "GEMOC Studio"
date: 2020-03-12T09:08:10-04:00
logo: "/images/research/gemoc_studio.png"
tags: ["Modeling"]
homepage: "http://gemoc.org/studio.html"
facebook: ""
linkedin: ""
twitter: "https://twitter.com/gemocinitiative"
youtube: ""
funding_bodies: []
eclipse_projects: ["modeling.gemoc"]
project_type: success
summary: "GEMOC Studio offers a framework for designing and integrating EMF-based modeling languages."
---
The Eclipse GEMOC Studio offers a framework for designing and integrating EMF-based modeling languages. The framework provides a generic interface to plug in different execution engines associated to their specific metalanguages used to define the discrete-event operational semantics, and the behavioral coordination, of DSLs. It also integrates generic runtime services that are shared among the approaches used to implement the execution semantics, such as graphical animation or omniscient debugging.

Based on a common API, GEMOC proposes a framework to integrate any kind of metaprogramming approach used to define discrete-event operational semantics into an execution engine. An engine is developed using the execution framework and is specific to a metaprogramming approach. The project offers different engines implementation. Since a significant part of the logic is common to all execution engines, the framework provides a basic abstract execution engine that can be extended into a concrete engine for any new metaprogramming approach.

Notably, implementing this API allows to use and reuse of generic or user-defined runtime services as add-ons(extensions) that send and receive generic messages to and from the execution engines. For example, the GEMOC framework offers a set of runtime services such as:

- generic debuggers that can be used for any executable DSL and engine.  
- efficient execution trace model  
- model animation  

The frameworks help to regulate interactions needed to support collaboration and work coordination across different system domains. Engines implementations that use the framework are then potentially eligible for coordination, i.e. being able to run a system described using different models optionally expressed in different languages. Such system can then be developed in an independent manner in order to meet the specific needs of domain experts. Yet the expert can see how their work on a particular aspect influences works on other concerns.

The framework and the initial engines are distributed through three technologies (update sites) that build on top of each other:

- the Sirius Animator technology focuses on the core execution framework and model debugging environment. It contains a set of generic runtime services that can be shared among the different execution engines (facilities for debugging, graphical/textual animation, and execution trace management). It also contains a Java-based execution engine.   
- the MoCCML / Concurrency focuses on explicit concurrency constraints within execution semantics.  
- the BCOoL / Coordination technology focuses on explicit concurrency constraints in between execution semantics.  

In addition, the project defines an Eclipse RCP, namely the GEMOC Studio, which provides a ready to use environment for both language designers (using the language workbench) and domain designers (using the modeling workbench).