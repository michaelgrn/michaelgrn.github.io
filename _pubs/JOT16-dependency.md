---
title: "Dependency Injection with Static Analysis and Context-Aware Policy"
date: 2016-02-01
project: tbd
type: paper
---

{: .citation}
Michael D. Ekstrand and Michael Ludwig. 2016. ["Dependency Injection with Static Analysis and Context-Aware Policy"](#). <cite>Journal of Object Technology, 15(1), 1-1</cite>.

## Abstract

The dependency injection design pattern improves the configurability, testability, and maintainability of object-oriented applications by decoupling components from both the concrete implementations of their dependencies and the strategy employed to select those implementations. In recent years, a number of libraries have emerged that provide automated support for constructing and connecting dependency-injected objects. Our experience developing systems with these tools has led us to identify two shortcomings of existing dependency injection solutions: the mechanisms for specifying component implementations often make it difficult to write and configure systems of arbitrarily-composable components, and the toolkit implementations often provide limited capabilities for inspection and static analysis of the object graphs of dependency-injected systems. We present Grapht, an new dependency injection container for Java that addresses these issues by providing context-aware policy, allowing component implementation decisions to depend on where in the object graph a component is required, and using a design that allows for static analysis of configured object graphs. To achieve its objectives, Grapht is built on a mathematical representation of dependency injection and object graphs that facilitates static analysis and straightforward implementation, and forms a basis for further consideration of the capabilities of dependency injection. The mathematical representation includes context-aware policy that we show to be strictly more expressive than the qualified dependencies used in many current toolkits. We demonstrate the utility of our of our approach with a case study showing how Grapht has aided in the development of the LensKit recommender systems toolkit.
## Links

* [Paper PDF](http://www.jot.fm/issues/issue_2016_01/article1.pdf)