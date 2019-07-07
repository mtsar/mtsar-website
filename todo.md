---
layout: page
title: TODO
description: Research and engineering ideas for Mechanical Tsar.
permalink: /todo/
---

Here are some research project ideas, engineering ideas for new participants, and areas where domain experts from other fields might add a lot of value by bringing their perspective into the Mechanical Tsar discussion.

* **Pricing Algorithms**
  * Microtasks often involve micropayments. Currently, Mechanical Tsar lacks the ability to estimate optimal task degree and price.

* **More Processors**
  * Mechanical Tsar offers a convenient API for implementing worker rankers, [task allocators](https://github.com/mtsar/mtsar/wiki/Writing-a-Task-Allocator) and answer aggregators. The more processors we have, the more flexible we are.

* **Groovy Testing**
  * Rewrite the unit tests in [Groovy](http://www.groovy-lang.org/) for making them shorter and more readable.

* **Switch to basepom**
  * Our [POM](https://github.com/mtsar/mtsar/blob/develop/pom.xml) seems to be too redundant, so it might be reasonable to use the [basepom](https://github.com/basepom/basepom) `minimal` or `foundation` settings as the parent POM.

* **No JitPack**
  * [JitPack](https://jitpack.io/) is a great repository for hosting JVM libraries, however we need only a couple of modules not present in Maven Central: [Get Another Label](https://github.com/ipeirotis/Get-Another-Label) and [SQUARE](https://github.com/utir/square).

<!--
* **Topic**
  * Description.
-->

*This page is inspired by the page [HadoopResearchProjects](https://wiki.apache.org/hadoop/HadoopResearchProjects) on the Hadoop Wiki.*
