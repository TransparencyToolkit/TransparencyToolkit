Transparency Toolkit
====================

Transparency Toolkit is data collection, archiving, and analytics software for journalists, activists, and human rights researchers. This repository is the central place to download and run all of our tools.

This repository is to outline, project manage, and issue track all the various tools [TransparencyToolkit](https://transparencytoolkit.org) is creating.

Our tools are primarily made for investigative journalists and researching various open source intelligence sources. All of our tools are open source. We could love to collaborate and receiving contributions. We also conduct our own original research, mostly on the international surveillance industry.

Interested in collaborating or contributing [contact us](info@transparencytoolkit.org) 

## LookingGlass

A highly configurable web application for viewing JSON datasets in a themeable faceted search interface.

**Examples**

- [ICWATCH](https://icwatch.wikileaks.org)
- [Snowden Doc Search](https://search.edwardsnowden.com)
- [Surveillance Industry Index](https://sii.transparencytoolkit.org)

**Technical**

- Ruby, Rails, ElasticSearch, JS, SASS, Bootstrap
- [Browse Code](https://github.com/TransparencyToolkit/LookingGlass)

---

## Harvester

A rails application that provides a web interface to run all of our scrapping tools and integrates with LookingGlass

**Technical**

- Technologies: Ruby, Rails, neo4j, JS, SASS, Bourbon
- [Browse Code](https://github.com/TransparencyToolkit/Harvester)

---

## Components

- [CrawlerManager](https://github.com/TransparencyToolkit/CrawlerManager) - an
  API for running and managing crawlers
- [KeepGrabbing](https://github.com/TransparencyToolkit/KeepGrabbing) - a
  collection of scripts and CLIs to manage and run scrappers and crawlers

---

## Gems

- [RequestManager](https://github.com/TransparencyToolkit/RequestManager)
- [DirCrawl](https://github.com/TransparencyToolkit/DirCrawl)
- [ParseFile](https://github.com/TransparencyToolkit/ParseFile)
- [EmailParser](https://github.com/TransparencyToolkit/EmailParser)
- [LinkedInCrawler](https://github.com/TransparencyToolkit/LinkedInCrawler)
- [IndeedCrawler](https://github.com/TransparencyToolkit/IndeedCrawler)
- [PiplRequest](https://github.com/TransparencyToolkit/PiplRequest)
- [PiplCollector](https://github.com/TransparencyToolkit/PipleCollector)

---

## Misc

- [Twiddler](https://github.com/TransparencyToolkit/Twiddler) - an experimental
  tool to help with processing, refining, and extracting meaning from text and file dumps
- [ArchivePile](https://github.com/TransparencyToolkit/ArchivePile) - a TT
  inspired read-only theme for browsing email archives that runs on Mailpile
