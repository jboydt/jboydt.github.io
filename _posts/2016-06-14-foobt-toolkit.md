---
title: foobt.net toolkit
layout: post
---

I have done a **lot** of experimentation over the last two weeks and have finally decided to use the following as my toolkit to rework/rewrite [foobt.net](http://foobt.net):

1. Database
* [MongoDB](https://www.mongodb.com/)
2. Backend
* [Ring](https://github.com/ring-clojure/ring) (HTTP server abstraction)
* [Compojure](https://github.com/weavejester/compojure) (Routing)
* [Cheshire](https://github.com/dakrone/cheshire) (JSON encoding)
* [Monger](http://clojuremongodb.info/) (MongoDB client)
* [Hiccup](https://github.com/weavejester/hiccup) (HTML rendering)
2. CSS
* [Spectre](https://picturepan2.github.io/spectre/) (Using a custom build so I can control color palette, et al.)

I still have to make a decision about frontend scripting. [jQuery](https://jquery.com/) will be in the mix, and I may end up using [ClojureScript](https://github.com/clojure/clojurescript) to have end-to-end Clojure.

And I may use one or more of the following to assist with HTML templating/rendering:

* [hiccups](https://github.com/teropa/hiccups) (ClojureScript port of [hiccup](https://github.com/weavejester/hiccup))
* [Hickory](https://github.com/davidsantiago/hickory) (Parse HTML into Clojure/hiccup data structures)
* [hiccup-bridge](https://github.com/hozumi/hiccup-bridge) (hiccup->HTML, HTML->hiccup)

And I am trying to use [Scalable Vector Graphics](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics) (SVG) throughout. The resources I have leaned on for SVG graphics so far are:

* [IcoMoon](https://icomoon.io/)
* [Devicon](http://devicon.fr/)
* [Method Draw](http://editor.method.ac/)

Effectively, I have scrapped all of the frameworks and I am building my site from the ground up. The frameworks were just not doing it for me.