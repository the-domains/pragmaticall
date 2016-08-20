---
datePublished: '2016-08-20T14:23:02.450Z'
sourcePath: _posts/2016-08-20-the-mizuiro-effect.md
author: []
via: {}
dateModified: '2016-08-20T14:20:40.943Z'
title: The mizuiro effect
publisher: {}
description: The linguistic relativity principle
starred: false
inFeed: true
hasPage: false
inNav: false
_type: MediaObject

---
# The mizuiro effect

> Each language and each model has its strengths and limitations. A language can sensitize you to certain types of issues, but at the same time it may leave you with a blind spot for other types of issues. I call that the Mizuiro effect. A business analyst should be aware of the strengths and limitations of each language and each model (s)he uses. By applying at least two complementary languages or models, the business analyst can reduce the risk of omissions.

**The linguistic relativity principle**

In 1940 Benjamin Lee Whorf introduced the "linguistic relativity principle":

> _"users of markedly different grammars are pointed by their grammars toward different types of observations and different evaluations of externally similar acts of observation, and hence are not equivalent as observers but must arrive at somewhat different views of the world"._

At first many people were sceptical about this principle. Nowadays there is a lot of scientific evidence to support a certain amount of influence of grammar on cognition. One example is the paper by Athanasopoulos et al: "[Representation of colour concepts in bilingual cognition: The case of Japanese blues.][0]"

Japanese divides the blue region of colour space into a darker shade called 'ao' and a lighter shade called 'mizuiro'. English does not have two distinct words (just 'blue' , which can be modified to 'dark blue' or 'light blue'. The paper shows that Japanese bilinguals who used English more frequently distinguished blue and light blue less well than those who used Japanese more frequently. The authors conclude that linguistic categories affect the way speakers of different languages evaluate objectively similar perceptual constructs.

When I first read this, it reminded me of the "[Eskimo words for snow][1]" claim. This is the (apparently not entirely correct) claim that Eskimos have an unusually large number of words for snow.

Though this particular claim may not be entirely correct, recent research like "The case of Japanese blues" does show that language affects our perception (and possibly vice versa), at least to some extent. It seems each language has its strengths and weaknesses. My guess is that the Eskimo-Aleut languages are strong at specifying different snowy conditions, but weak at distinguishing varieties of tropical hardwood trees.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/4dd331e6-a65d-468d-a9ac-f44d36dbec05.jpg)

**Strengths and limitations of language**

The strengths and limitations of language also impact my work as a business analyst, in many different ways. For example:

* Natural language is inherently ambiguous.
* Subject matter experts often have their own specialized vocabulary.

Models and many requirements specification techniques are languages of a sort. I see them as highly specialized languages designed for a particular purpose. Being specialized exaggerates the Mizuiro effect: a specialized language is great for analyzing or specifying the kind of issues that is was designed for, but often hopelessly inadequate for other issues. Take use cases for example: they are great for identifying & specifying tasks to be performed by the system, but not so good for describing concepts and the relationships between concepts.

**Complementary languages**

If you are aware of the strengths and limitations of the languages, models and techniques you use (lets just call then languages for simplicity), then you can apply those languages effectively. In most cases you will have to use different languages, and those languages must complement each other: the strengths of one language make up for the limitations of the other. In that context, [Stephen Ferg's analogy with chocolate][2] is quite entertaining.

This is true regardless of the development approach being used: waterfall, agile or any other approach shouldn't rely on a single language. (Yes, dear Scrum practitioners, this applies to you too. Only using user stories to the exclusion of all else is risky. Why not throw in a data dictionary or the odd decision table?)

**Further reading**

The influence of the Mizuiro effect on business analysis & requirements specification has been recognized a long time ago, and there are many approaches to provide guidance on how to deal with it. A relatively old and very extensive example is the [Zachman framework][3]. My personal favourites on this topic are:

Ian Alexander. Ian's book '[Discovering Requirements][4]' (with Ljerka Beus-Dukic) is based around a matrix consisting of requirements elements (stakeholders, goals, context, scenarios, qualities and constraints, rationale, definitions, measurements, priorities) and discovery contexts (from individuals, from groups, from prototypes, from archeology, from standards & templates, from trade-offs).

Soren Lauesen. Soren's book "[Software Requirements -- Styles and Techniques][5]" groups techniques into e.g. data requirement styles, functional requirement styles, functional details, interfaces, and quality requirements. He lists the advantages and disadvantages for each technique.

Ellen Gottesdiener. Ellen is my favourite when it comes to this topic. It features in all her books, but I particularly recommend her brand new book [Discover to Deliver][6] (with Mary Gorman). The book introduces an 'Options Board' with 7 product dimensions: user, interface, action, data, control, environment, and quality attribute.

**Don't be blue**

We are all affected by the Mizuiro effect, and our requirements models are too. I try to turn it into my advantage by combining multiple complementary languages. How do you deal with the Mizuiro effect?

[0]: http://journals.cambridge.org/abstract_S1366728909990046 "The case of Japanese blues"
[1]: http://en.wikipedia.org/wiki/Eskimo_words_for_snow "Wikipedia: eskimo words for snow"
[2]: http://www.jacksonworkbench.co.uk/stevefergspages/papers/ferg--whats_wrong_with_use_cases.html "What's wrong with use cases?"
[3]: http://www.zachman.com/about-the-zachman-framework "About the Zachman framework"
[4]: http://eu.wiley.com/WileyCDA/WileyTitle/productCd-0470712406.html "Book: Discovering Requirements"
[5]: http://www.pearsonhighered.com/educator/product/Software-Requirements-Styles-Techniques/9780201745702.page "Book: Software Requirements Styles and Techniques"
[6]: http://www.discovertodeliver.com/ "Book: Discover to Deliver"