---
title: "Exploring research subject areas"
---


Many academic journals describe the articles they publish using topical keywords, which authors can specify ad-lib, or select from a controlled vocabulary provided by the publisher. [PLOS](http://www.plos.org/) stands out in the sophistication of its approach: articles are associated with [subject areas](http://www.plosone.org/static/help#subjectAreas) from a thesaurus of over 10000 terms, with specific associations established by machine-aided indexing. Probably to avoid overwhelming readers, the PLOS website's [subject area list](http://www.plosone.org/taxonomy) only shows the first two tiers of a taxonomy that goes up to ten tiers deep. Now, you can explore the PLOS subject areas in all their depth and beauty...

<div class="fig"><a href="{{ site.url }}/assets/PLOS-chem-rxns.png" target="blank"><img src="{{ site.url }}/assets/PLOS-chem-rxns.png" alt="PLOS Cloud Explorer screenshot" style="max-width: 1440px;"></a></div>

This spring, I took a course at the UC Berkeley School of Information called [Working with Open Data](http://www.ischool.berkeley.edu/courses/i290t-wod). I joined Anna Swigart and Colin Gerber in a class project, setting out to do something neat with open data and scientific research publications. Naturally, we looked to PLOS as a source of open data. As a publisher of open access journals, their articles and metadata are all Creative Commons licensed (CC-BY). They have an open [search API](http://api.plos.org/) as well. When we asked them about the thesaurus of subject areas, PLOS kindly provided us with a copy of the full subject area list.

What we ended up making is a web app that lets you explore what research in PLOS journals is about, how different fields of research are interrelated, and how that has changed over time.

**Check it out: [PLOS Cloud Explorer](http://groups.ischool.berkeley.edu/ploscloudexplorer/).**

I'll leave the details of what this does and how it works for your independent discovery. You can also read our documentation, and find our source code and data, [on GitHub](https://github.com/cmgerber/PLOS_Cloud_Explorer).

One of our reasons for making PLOS Cloud Explorer was that the fabulous complexity of PLOS's classification of research articles hasn't really been surfaced anywhere. With a visualization and some simple statistics, we can showcase the interconnectedness of research areas. For instance, look at the histogram of top-level subject areas for any node; because each article receives more than one classification, you'll see that PLOS articles tend to be associated with a mix of different fundamental fields. By the way, the thesaurus is not just a taxonomy, it's a [polyhierarchy](http://en.wiktionary.org/wiki/polyhierarchy): some subject areas belong to more than one higher-level area---such as psychology, which is included under both life sciences and social sciences.

What you see in PLOS Cloud Explorer is based on data about *all* the articles published in PLOS journals up until we assembled the data set, and represents a snapshot of the PLOS Thesaurus in its current state of [evolution](http://blogs.plos.org/tech/thesaurus-evolution/). Therefore, we'll need to update it from time to time to reflect more recent articles and changes in the subject areas *[update: refreshed full dataset on 02014-07-21]*. We'll probably also continue to make improvements in the web app as time goes on---such as linking to specific articles. 

**Update 02014-07-24:** This project is the subject of a [guest post on the PLOS Tech Blog](http://blogs.plos.org/tech/delving-subject-areas-plos-cloud-explorer/).