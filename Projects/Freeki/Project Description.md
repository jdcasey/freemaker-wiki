<!-- Freeki metadata. Do not remove this section!
TITLE: Project Description
-->
#Project Description

Freeki is a wiki system designed from the ground up to be as minimal as possible in terms of the server that runs it. The application started out as a training exercise to learn the Vert.x Java API, and turned into a fun challenge to see how much functionality I could add to something so small.

## Technology

Freeki is driven by a small collection of APIs:

- [Vert.x](http://vertx.io/) provides the HTTP framework
- [Groovy](http://groovy.codehaus.org/) provides the foundations for the templating engine used to render the basic page structures.
- [Gson](http://code.google.com/p/google-gson/) provides the API for customized `object <-> JSON` translation, for talking to the Javascript user interface via [REST](http://en.wikipedia.org/wiki/Representational_state_transfer) services.
- [jQuery](http://jquery.com/) is used to make the Javascript UI easier to manage.