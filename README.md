# Domain Driven Design in dynamic languages
This is an attempt to collect all info about Domain Driven Design the World knows in dynamic languages (Python, Ruby, PHP etc). Not only DDD but all worthy info about layered and clean architecture with separation of business logic from infrastructure and framework code.

So let's go!

## Stack exchange resources
[Separation of business logic and data access in django](http://stackoverflow.com/q/12578908/3606603) - Python, Django

[Why does domain driven design seem only popular with static languages like C♯ & Java?](http://stackoverflow.com/q/4201846/3606603)

[Domain Driven Design efforts in dynamic languages?](http://stackoverflow.com/q/1748577/3606603)

[DDD - Domain Driven Design, which development order should be applied?](http://programmers.stackexchange.com/q/235170/237421) - Python

[Retrieving aggregates from inside of other aggregates](http://stackoverflow.com/q/29456899/3606603) - StackOverflow question about aggregates in Python application

## Slides founded in slideshare or anywhere else
[Hexagonal design in Django](http://www.slideshare.net/mvschaik/hexagonal) - Python, Django, contains some code.

[Domain Driven Design com Python](http://www.slideshare.net/FredericoCabral2/domain-driven-design-com-python) - slides in Portuguese, but contains some useful code in Python

[Clean Architecture Python (web) apps](http://slides.com/haxoza/clean-architecture-python#/) - Przemek Lewandowski about application of Uncle Bob's Clean Architecture to Python web apps with code examples and type annotations

[From Active Record to Events](https://www.slideshare.net/emadb/wroclove-rb) - Emanuele DelBono about using DDD/CQRS/ES in ruby on rails applications

## Articles, blogs etc
[DDD for Rails developers](https://www.sitepoint.com/series/ddd-for-rails-developers/) - whole blog by Victor Savkin about DDD in Ruby on Rails

[Domain-Driven Design and MVC Architectures](https://blog.fedecarg.com/2009/03/11/domain-driven-design-and-mvc-architectures/) - two articles from Federico Cargnelutti with PHP examples in second part

[Value Objects in Java & Python](http://web.archive.org/web/20170910110903/https://stevewedig.com/2014/07/31/value-objects-in-java-and-python/) - about `Value Object`, comparison of value objects in Java and Python

[Domain Driven Design methodic Python](https://github.com/anthony-tresontani/methodic-python/blob/master/DomainDrivenDesign.rst) - A little summary about DDD in Python

[Exploring domains with python](http://www.ballofcode.com/python/domain-driven-design/2013/12/22/exploring-domains-with-python) - A little article with example of `Repository` and `Storage` classes

[Clean architectures in Python: a step-by-step example](http://blog.thedigitalcatonline.com/blog/2016/11/14/clean-architectures-in-python-a-step-by-step-example/) - Implementation of Uncle Bob's Clean Architecture in Python. Contains step by step explanation and github repo with all code.

[Large web apps in Python: A good architecture](http://dev.nando.audio/2014/04/01/large_apps_with_sqlalchemy__architecture.html) - Article with a point that MVC is not enough for large applications and you need separate layer for business logic.

[DDD + Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - A subreddit for Ruby developers interested in Domain-Driven Design.

[Arkency blog and newsletter](http://blog.arkency.com/) - They write about DDD, Event Sourcing and testing in Ruby/Rails a lot. Not just plain text, but code and even webinars occasionally.

[Hanami em Production – 2 anos depois](https://diariodebordo.creditas.com.br/hanami-em-production-2-anos-depois-parte-1/): post in Portuguese describing the experience of [Creditas](https://www.creditas.com.br/) at building and maintaining its core app (60k lines of code + 2m request/month) with DDD in Ruby using [Hanami](#user-content-hanami) framework.

[How to Improve on Naming Contexts in Domain-Driven Design](https://userinterfacing.com/how-to-improve-on-naming-contexts-in-domain-driven-design/) - Describes technique of how to find a better name for your bounded contexts.

## Talks, videos
[Domain-Driven Design with Python](https://skillsmatter.com/skillscasts/5025-domain-driven-design-with-python) - Great talk about DDD and Python with explanations of many DDD topics and code examples by Robert Smallshire from Skills Matter

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

## Code, code, code!
[Ruby DDD Sample App](https://github.com/paulrayner/ddd_sample_app_ruby) - Port of DDD Sample Application written in Java in Ruby. Definitely worth reading.

[DDD in Django](https://github.com/basco-johnkevin/ddd-python-django) - An attempt to implement DDD and hexagonal architecture in Django

[DDD in Flask](https://github.com/MichaelDiBernardo/ddd-flask-example) - A terse example of DDD-inspired architecture using Flask

[Kanban in Python](https://bitbucket.org/sixty-north/d5-kanban-python) - Python implementation of simple kanban board with DDD approach.

[Kanban in Clojure](https://bitbucket.org/sixty-north/d5-kanban-clojure) - Same in Clojure

[Kanban in Python exercises](https://bitbucket.org/sixty-north/d5-workshop-exercises-student-material) - Same board devided on exercises for students of some workshop by Sixty-North. 

[Rewind](https://github.com/JensRantil/rewind) - Rewind is a (CQRS) event store server written in Python. Not that it written with DDD approach but still related.

[The Clean Architecture with Python](https://www.reddit.com/r/Python/comments/41llbh/the_clean_architecture_with_python/) - Reddit discussion about the topic and [this](https://gist.github.com/justanr/1f38e09caad47bd0d927) gist with proposed architecture and some comments on it.

[abidria-api](https://github.com/jordifierro/abidria-api) - Django application written with clean architecture. There also an [article](https://engineering.21buttons.com/clean-architecture-in-django-d326a4ab86a9) by Jordi Fierro which explains architecture components and how they interact with each other.

<a name="hanami" href="http://hanamirb.org/">Hanami-rb</a> - A good option out of the Rails world, Hanami is an emerging framework that encourages and helps to design DDD applications in Ruby. The [getting started guide](http://hanamirb.org/guides/1.1/getting-started/) references some DDD concepts and how they fit inside the framework.

[Revents](https://github.com/emadb/revents) - A possibile implementation of a DDD/CQRS/ES in Ruby and Ruby on Rails

## Training

[DDD Patterns in Python](http://sixty-north.com/domain_driven_design_in_python.html) - Sixty North offers two-day classroom training on implementing DDD in Python with relational or event-sourced persistence. (Paid)
