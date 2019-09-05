---
title: "Mapping the safer chemical substitution knowledge network"
show_title: true
---

This is a _partial and incomplete_ graph of knowledge resources for safer chemical substitution and how they're connected. It's meant to show that many interrelated resources support the practices of chemical hazard assessment and alternatives assessment, and that these resources build on each another. <a href="#about">See below</a>.

Click a node or link to see details about it. Group and arrange the network in different ways. There's also a [full-page view](https://kaios.net/safer-chemicals-network/).

{% include network.html %}

<h2 id="about">About this graph</h2>

My [research project]({{ site.url }}/research) is about shared knowledge resources for chemical hazard assessment and [alternatives assessment](https://en.wikipedia.org/wiki/Alternatives_assessment). The goal of this data visualization is to illustrate a network of relationships between individual knowledge resources, making up a broader *knowledge commons*.

The goal is to be selective, not comprehensive. I've focused on assessment methods—particularly the [GreenScreen for Safer Chemicals](https://www.greenscreenchemicals.org)—and the resources that are linked to them. The map is essentially incomplete, and in this description I'll try to explain its boundaries. This may evolve over time.

### Data representation and description

Each node represents a resource or a set of closely-linked resources. This is a very broad category of things that includes data, methodologies, standards, programs, services, organizations, and policies. All of these things participate in flows of knowledge. Links in the network represent these flows of knowledge.

All nodes and links are described with text and references, which you can see in an information card when you click on them. I also classify nodes with three attributes, which are used to group and arrange them visually:

- **Resource type:** To make rough distinctions between different kinds of resources
- **Design level:** Because different resources focus on different scopes of design—chemical, formulation, material, product
- **Industry sector:** Some resources have a specific industrial domain of applicability

### What's included in the map?

The map currently includes some of the following kinds of knowledge resources.

- **Methods** for chemical hazard assessment (CHA) & alternatives assessment (AA)
- **Standards** and **certification programs** that include a CHA element, no matter how simple
- **Policy programs** that incorporate AA into the governance of chemicals, even if only partially
- **Data resources** that are about safer chemical substitution, or at least highly relevant to CHA
- **Chemical assessors**—entities, such as consulting firms, that produce CHA knowledge using methods and data
- **Platforms**, which incorporate CHA & AA into knowledge products and services that coordinate multiple business functions

### What do the links mean?

Links represent flows of knowledge that are variable and unique to each link (click for details). They can be generalized to the following kinds of relationships, expressed as verbs:

- **Includes by reference:** For example, methods and policies invoke or require the use of other resources
- **Operationalizes or performs:** Such as when a software tool operationalizes a chemical screening protocol
- **Provides:** Resources may produce new knowledge or aggregate knowledge of another kind

Rather than classify all links with one of these generic verbs, I’ve decided to include a more complete textual description of what each link means, with references, in the information card.

I also don't show the direction of links (i.e. A → B) in the graph. The links can be considered directed, but I don't think this is either clear enough or important enough to display all at once. Instead, the description of each link tells you what you need to know about its directionality.

### What's left out?

Lists of chemicals (such as regulatory and hazard classification lists), and the relationships between these lists, are not shown in this map. While they are included by reference in many CHA resources, these lists are numerous, and mapping the relationships between them could be a whole other project.

### Feedback & development

I welcome feedback and input on this map. The data and source code, along with ways to give feedback, are [available on GitHub](https://github.com/akokai/safer-chemicals-network).
