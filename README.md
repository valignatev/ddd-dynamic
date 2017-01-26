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

## Articles, blogs etc
[DDD for Rails developers](https://www.sitepoint.com/series/ddd-for-rails-developers/) - whole blog by Victor Savkin about DDD in Ruby on Rails

[Domain-Driven Design and MVC Architectures](https://blog.fedecarg.com/2009/03/11/domain-driven-design-and-mvc-architectures/) - two articles from Federico Cargnelutti with PHP examples in second part

[Value Objects in Java & Python](https://stevewedig.com/2014/07/31/value-objects-in-java-and-python/) - about `Value Object`, comparison of value objects in Java and Python

[Domain Driven Design methodic Python](https://github.com/anthony-tresontani/methodic-python/blob/master/DomainDrivenDesign.rst) - A little summary about DDD in Python

[Exploring domains with python](http://www.ballofcode.com/python/domain-driven-design/2013/12/22/exploring-domains-with-python) - A little article with example of `Repository` and `Storage` classes

[Clean architectures in Python: a step-by-step example](http://blog.thedigitalcatonline.com/blog/2016/11/14/clean-architectures-in-python-a-step-by-step-example/) - Implementation of Uncle Bob's Clean Architecture in Python. Contains step by step explanation and github repo with all code.

[Large web apps in Python: A good architecture](http://nando.oui.com.br/2014/04/01/large_apps_with_sqlalchemy__architecture.html) - Article with a point that MVC is not enough for large applications and you need separate layer for business logic.

## Talks, videos
[Domain-Driven Design with Python](https://skillsmatter.com/skillscasts/5025-domain-driven-design-with-python) - Great talk about DDD and Python with explanations of many DDD topics and code examples by Robert Smallshire from Skills Matter

[The Clean Architecture in Python](https://www.youtube.com/watch?v=DJtef410XaM) - Awesome talk on PyOhio2014 from Brandon Rhodes

[Hexagonal architecture in Django](https://www.youtube.com/watch?v=tKEv9Enhm1Q) Talk in Russin, contains code examples and project layout

[Domain Driven Design and Hexagonal Architecture with Rails](https://www.youtube.com/watch?v=_rbF97T4480) - Ruby on Rails talk from RailsConf 2014 by Eric Roberts and Declan Whelan with code examples

[Hexagonal Rails](https://www.youtube.com/watch?v=CGN4RFkhH2M) - Ruby on Rails, GoRuCo 2012 by Matt Wynne

[Hexagonal Architecture in DDD](https://www.youtube.com/watch?v=u6oTg5oRH24) - Golf with DDD in PHP by Gordon Skinner from PHP UK Conference

[Boundaries Python](https://www.youtube.com/watch?v=eOYal8elnZk) - Talk about `Boundaries` by Gary Bernhardt from Pycon US 2013

[Boundaries Ruby](https://www.youtube.com/watch?v=yTkzNHF6rMs) - Same talk by Gary Bernhardt but in Ruby from Ruby Conf 12. Contains QA section.

[Hexagonal TDD](https://www.youtube.com/channel/UCCptggI2qaxsBXiwfit6tNQ) - TDD implementation of hexagonal architecture of rails application. In 3 parts.

[Jim Weirich on Decoupling from Rails](https://www.youtube.com/watch?v=tg5RFeSfBM4) - Showcase from Jim Weirich from October CincyRb.

## Code, code, code!
[Ruby DDD Sample App](https://github.com/paulrayner/ddd_sample_app_ruby) - Port of DDD Sample Application written in Java in Ruby. Definitely worth reading.

[DDD in Djnago](https://github.com/basco-johnkevin/ddd-python-django) - An attempt to implement DDD and hexagonal architecture in Django

[DDD in Flask](https://github.com/MichaelDiBernardo/ddd-flask-example) - A terse example of DDD-inspired architecture using Flask

[Kanban in Python](https://bitbucket.org/sixty-north/d5-kanban-python) - Python implementation of simple kanban board with DDD approach.

[Kanban in Clojure](https://bitbucket.org/sixty-north/d5-kanban-clojure) - Same in Clojure

[Kanban in Python exercises](https://bitbucket.org/sixty-north/d5-workshop-exercises-student-material) - Same board devided on exercises for students of some workshop by Sixty-North. 

[Rewind](https://github.com/JensRantil/rewind) - Rewind is a (CQRS) event store server written in Python. Not that it written with DDD approach but still related.

## Training

[DDD Patterns in Python](http://sixty-north.com/domain_driven_design_in_python.html) - Sixty North offers two-day classroom training on implementing DDD in Python with relational or event-sourced persistence.
