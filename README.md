# Domain Driven Design in dynamic languages
This is an attempt to collect all info about Domain Driven Design the World knows in dynamic languages (Python, Ruby, PHP etc). Not only DDD but all worthy info about layered and clean architecture with separation of business logic from infrastructure and framework code.

So let's go!

## Books

[Architecture Patterns with Python (aka "Cosmic Python")](https://github.com/python-leap/book/) - Book by Harry Percival and Bob Gregory featuring DDD and strategic patterns (forthcoming on O'Reilly, also available in [early release on safari](https://learning.oreilly.com/library/view/enterprise-architecture-patterns/9781492052197/)

[Clean Architectures in Python](https://leanpub.com/clean-architectures-in-python) - Book by Leonardo Giordani based on [his](http://blog.thedigitalcatonline.com/blog/2016/11/14/clean-architectures-in-python-a-step-by-step-example/) post

[Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - a book by Robert Pankowecki & Arkency Team about DDD, CQRS, Event Sourcing related to Rails projects

[Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Book by Carlos Buenosvinos, Christian Soronellas, and Keyvan Akbary about DDD and implement with PHP

[Event Sourced Building Blocks for Domain Driven Design with Python](https://leanpub.com/eventsourcedddesignwithpython) - This small book contains a concise pattern language for event sourced DDD in Python. This book focuses on reliable "building blocks" for DDD. It avoids reprising the "strategic" patterns of DDD. It takes a practical "bottom up" approach to making reliable, scalable, maintainable applications and systems. The preface includes a rejuventated consideration of pattern language as description of events. This is a small book, and isn't quite finished at this time.

[Implementing the Clean Architecture](https://leanpub.com/implementing-the-clean-architecture) - a book focusing on practical aspects of implementing the Clean Architecture. It is heavily illustrated by code snippets in Python. Apart from the Clean Architecture itself, it also introduces other software engineering patterns, like modularity, Dependency Injection. CQRS or Event Sourcing. 

## Stack exchange resources
[Separation of business logic and data access in django](http://stackoverflow.com/q/12578908/3606603) - Python, Django

[Why does domain driven design seem only popular with static languages like C♯ & Java?](http://stackoverflow.com/q/4201846/3606603)

[Domain Driven Design efforts in dynamic languages?](http://stackoverflow.com/q/1748577/3606603)

[DDD - Domain Driven Design, which development order should be applied?](http://programmers.stackexchange.com/q/235170/237421) - Python

[Retrieving aggregates from inside of other aggregates](http://stackoverflow.com/q/29456899/3606603) - StackOverflow question about aggregates in Python application

## Slides found in slideshare or anywhere else

[Avoiding the domino effect in our services (SOLID at macro-design level)](https://www.slideshare.net/CodelyTV/avoiding-the-domino-effect-in-our-microservices-solid-at-macrodesign-level)

[Clean Architecture Python (web) apps](http://slides.com/haxoza/clean-architecture-python#/) - Przemek Lewandowski about application of Uncle Bob's Clean Architecture to Python web apps with code examples and type annotations

[Domain Driven Design com Python](http://www.slideshare.net/FredericoCabral2/domain-driven-design-com-python) - slides in Portuguese, but contains some useful code in Python

[From Active Record to Events](https://www.slideshare.net/emadb/wroclove-rb) - Emanuele DelBono about using DDD/CQRS/ES in ruby on rails applications

[From framework coupled code to microservices through DDD](https://www.slideshare.net/CodelyTV/from-framework-coupled-code-to-microservices-through-ddd-modules-by-codelytv)

[Hexagonal design in Django](http://www.slideshare.net/mvschaik/hexagonal) - Python, Django, contains some code.

[Microservices: Improving the autonomy of our teams with Event-Driven Architecture](https://www.slideshare.net/CodelyTV/microservices-improving-the-autonomy-of-our-teams-with-eventdriven-architecture-cas2018)

## Articles, blogs etc

[DDD for Rails developers](https://www.sitepoint.com/series/ddd-for-rails-developers/) - whole blog by Victor Savkin about DDD in Ruby on Rails

[Domain-Driven Design and MVC Architectures](https://blog.fedecarg.com/2009/03/11/domain-driven-design-and-mvc-architectures/) - two articles from Federico Cargnelutti with PHP examples in second part

[Value Objects in Java & Python](http://web.archive.org/web/20170910110903/https://stevewedig.com/2014/07/31/value-objects-in-java-and-python/) - about `Value Object`, comparison of value objects in Java and Python

[Domain Driven Design methodic Python](https://github.com/anthony-tresontani/methodic-python/blob/master/DomainDrivenDesign.rst) - A little summary about DDD in Python

[Exploring domains with python](http://www.ballofcode.com/python/domain-driven-design/2013/12/22/exploring-domains-with-python) - A little article with example of `Repository` and `Storage` classes

[Clean architectures in Python: a step-by-step example](http://blog.thedigitalcatonline.com/blog/2016/11/14/clean-architectures-in-python-a-step-by-step-example/) - Implementation of Uncle Bob's Clean Architecture in Python. Contains step by step explanation and github repo with all code.

[DDD with Ports and Adapters in Python](https://io.made.com/introducing-command-handler/) from the made.com tech blog, followed by [Repository and Unit of Work Pattern in Python](https://io.made.com/repository-and-unit-of-work-pattern-in-python/), [CQRS / Handlers and Views](https://io.made.com/commands-and-queries-handlers-and-views/) and [Why use Domain Events?](https://io.made.com/why-use-domain-events/)

[Large web apps in Python: A good architecture](http://dev.nando.audio/2014/04/01/large_apps_with_sqlalchemy__architecture.html) - Article with a point that MVC is not enough for large applications and you need separate layer for business logic.

[DDD + Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - A subreddit for Ruby developers interested in Domain-Driven Design.

[Arkency blog and newsletter](http://blog.arkency.com/) - They write about DDD, Event Sourcing and testing in Ruby/Rails a lot. Not just plain text, but code and even webinars occasionally.

[Hanami em Production – 2 anos depois](https://diariodebordo.creditas.com.br/hanami-em-production-2-anos-depois-parte-1/): post in Portuguese describing the experience of [Creditas](https://www.creditas.com.br/) at building and maintaining its core app (60k lines of code + 2m request/month) with DDD in Ruby using [Hanami](#user-content-hanami) framework.

[How to Improve on Naming Contexts in Domain-Driven Design](https://userinterfacing.com/how-to-improve-on-naming-contexts-in-domain-driven-design/) - Describes technique of how to find a better name for your bounded contexts.

[Implementing Domain-Driven Design in PHP](https://dzone.com/articles/implementing-domain-driven-design-in-php) - Introduce Domain Driven Design and how to Implementing in Laravel with PHP by Alireza Rahmani Khalili.

[Event Sorcery](https://www.eventsorcery.com) - Detailed blog with lengthy articles about building event sourced domain driven applications with Python. 

## Talks, videos, Podcasts

[Domain-Driven Design with Python](https://skillsmatter.com/skillscasts/5025-domain-driven-design-with-python) - Great talk about DDD and Python with explanations of many DDD topics and code examples by Robert Smallshire from Skills Matter

[Domain-Driven Design Patterns in Python](https://www.youtube.com/watch?v=Ru2T4fu3bGQ) - Detailed talk about DDD patterns in Python by Robert Smallshire from EuroPython 2018

[The Clean Architecture in Python](https://www.youtube.com/watch?v=DJtef410XaM) - Awesome talk on PyOhio2014 from Brandon Rhodes

[Hexagonal architecture in Django](https://www.youtube.com/watch?v=tKEv9Enhm1Q) Talk in Russian by [@proofit404](https://github.com/proofit404), contains code examples and project layout

[Domain Driven Design and Hexagonal Architecture with Rails](https://www.youtube.com/watch?v=_rbF97T4480) - Ruby on Rails talk from RailsConf 2014 by Eric Roberts and Declan Whelan with code examples

[Hexagonal Rails](https://www.youtube.com/watch?v=CGN4RFkhH2M) - Ruby on Rails, GoRuCo 2012 by Matt Wynne

[Hexagonal Architecture in DDD](https://www.youtube.com/watch?v=u6oTg5oRH24) - Golf with DDD in PHP by Gordon Skinner from PHP UK Conference

[Boundaries Python](https://www.youtube.com/watch?v=eOYal8elnZk) - Talk about `Boundaries` by Gary Bernhardt from Pycon US 2013

[Boundaries Ruby](https://www.youtube.com/watch?v=yTkzNHF6rMs) - Same talk by Gary Bernhardt but in Ruby from Ruby Conf 12. Contains QA section.

[Hexagonal TDD](https://www.youtube.com/channel/UCCptggI2qaxsBXiwfit6tNQ) - TDD implementation of hexagonal architecture of rails application. In 3 parts.

[Jim Weirich on Decoupling from Rails](https://www.youtube.com/watch?v=tg5RFeSfBM4) - Showcase from Jim Weirich from October CincyRb.

[From Active Record to Events](https://www.youtube.com/watch?v=GaGBfDe7r9Y) - A talk by Emanuele DelBono from Wroclove.rb about DDD/CQRS/ES in Ruby and Ruby on Rails.

[Built to last: A domain-driven approach to beautiful systems](https://www.youtube.com/watch?v=52qChRS4M0Y) - RailsConf 2017 talk by Andrew Hao. Techniques for refactoring legacy codebase to DDD style, design overview and code examples. 

[Technically DDD](https://www.youtube.com/watch?v=JpcNeeetijo) - Fantastic talk by Pim Elshoff on getting started with DDD using Value Objects, Entities and Services in PHP

[Perhap: Applying Domain Driven Design and Reactive Architectures to Functional Programming](https://www.youtube.com/watch?v=kq4qTk18N-c) - a talk by Rob Martin from ElixirConf 2017.

[Clean Architecture](https://www.youtube.com/watch?v=18IqltQ4XE4) - PyGotham 2018 talk by Sebastian Buczyński with [code](https://github.com/Enforcer/clean-architecture-example-1) and [slides](https://cleanarchitecture.io/wp-content/uploads/2018/10/slides.pdf?189db0&189db0). There is also a [blog post](https://breadcrumbscollector.tech/the-clean-architecture-in-python-how-to-write-testable-and-flexible-code/) in English

[Domain Driven Design](https://www.youtube.com/watch?v=_CK5Kag7enw) - CODEiD 2018 talk by Артём Антоненко [@Antonyan](https://github.com/Antonyan). In Russian. There's also a repo - [PHP DDD Skeleton](https://github.com/Antonyan/ddd-skeleton), and other DDD-related projects under his github account.

[Eventsourcing 101](https://www.youtube.com/watch?v=0l8vuYaaBUs) - the talk about event sourcing with live coding in Python by Bob Gregory. He codes an event sourced e-commerce basket from scratch.

[Domain Driven Design For Python - Episode 219](https://www.pythonpodcast.com/domain-driven-design-episode-219/) - When your software projects start to scale it becomes a greater challenge to understand and maintain all of the pieces. In this episode Henry Percival shares his experiences working with domain driven design in large Python projects. 

[Как мы уменьшили сложность наших проектов](https://www.youtube.com/watch?v=45rk0iyTn7I) - PyCon RU 2019 talk by Борис Цема (in Russian) about using DDD patterns to reduce Wargaming.net projects.

[Clean Architectures in Python](https://www.youtube.com/watch?v=wtCQalq7L-E) - PyLondinium19 talk by Leonardo Giordani

## Code, code, code!

[Event Sourcing in Python](https://github.com/johnbywater/eventsourcing) - Mature, stable, popular Python library for event sourcing and DDD.

[real-world-domain-model](https://github.com/zarekr/python-real-world-domain-model) - Starts by building a domain model of a UK company using pure Python then adapts a TDD approach to add more detail, resulting in an accurate and complex domain layer that forms the basis for other tutorials on [eventsorcery.com](https://www.eventsorcery.com) about the Event Sourcing in Python library.

[python-eventsourcing-tutorial](https://github.com/zarekr/python-eventsourcing-tutorial) - Demonstrates how to use the Event Sourcing in Python library step-by-step. 

[dry-python](https://github.com/dry-python) - A set of Python libraries for pluggable business logic components.

[Ruby DDD Sample App](https://github.com/paulrayner/ddd_sample_app_ruby) - Port of DDD Sample Application written in Java in Ruby. Definitely worth reading.

[DDD in Django](https://github.com/basco-johnkevin/ddd-python-django) - An attempt to implement DDD and hexagonal architecture in Django

[DDD in Flask](https://github.com/MichaelDiBernardo/ddd-flask-example) - A terse example of DDD-inspired architecture using Flask

[Kanban in Python](https://bitbucket.org/sixty-north/d5-kanban-python) - Python implementation of simple kanban board with DDD approach.

[Kanban in Clojure](https://bitbucket.org/sixty-north/d5-kanban-clojure) - Same in Clojure

[Kanban in Python exercises](https://bitbucket.org/sixty-north/d5-workshop-exercises-student-material) - Same board devided on exercises for students of some workshop by Sixty-North. 

[Rewind](https://github.com/JensRantil/rewind) - Rewind is a (CQRS) event store server written in Python. Not that it written with DDD approach but still related.

[The Clean Architecture example application (python)](https://github.com/Enforcer/clean-architecture) - Repository with example modular application written in Python. The code is used in Implementing the Clean Architeure book.

[The Clean Architecture with Python](https://www.reddit.com/r/Python/comments/41llbh/the_clean_architecture_with_python/) - Reddit discussion about the topic and [this](https://gist.github.com/justanr/1f38e09caad47bd0d927) gist with proposed architecture and some comments on it.

[abidria-api](https://github.com/jordifierro/abidria-api) - Django application written with clean architecture. There also an [article](https://engineering.21buttons.com/clean-architecture-in-django-d326a4ab86a9) by Jordi Fierro which explains architecture components and how they interact with each other.

[Hanami](https://hanamirb.org/) - A good option out of the Rails world, Hanami is an emerging framework that encourages and helps to design DDD applications in Ruby. The [getting started guide](http://hanamirb.org/guides/1.1/getting-started/) references some DDD concepts and how they fit inside the framework.

[Hexagonal Architecture + DDD + CQRS applied in PHP using Symfony 4](https://github.com/CodelyTV/cqrs-ddd-php-example)

[Revents](https://github.com/emadb/revents) - A possibile implementation of a DDD/CQRS/ES in Ruby and Ruby on Rails

[DDD Rails Sample](https://github.com/mcapanema/ddd-rails-example) - project meant to be used as a start point for those who want to build Domain Driven Design applications in Rails.

[Domain Driven Design Classes and Interfaces](https://github.com/ericksonreyes/domain-driven-design) - The project is a PHP sample collection of Domain Driven Design inspired Classes and Interfaces.


## Paid training and workshops

[DDD Patterns in Python](http://sixty-north.com/domain_driven_design_in_python.html) - Sixty North offers two-day classroom training on implementing DDD in Python with relational or event-sourced persistence.

[Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - workshops by Arkency. The page should have a schedule for future workshops and a summary of what to expect from them.
