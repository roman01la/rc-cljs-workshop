# [ClojureScript Workshop](https://reactiveconf.com/workshop/introduction-to-clojurescript) @ [ReactiveConf '17](https://reactiveconf.com/2017/)

![](logo.png)

Timing: 4hrs (1:00 PM - 5:00 PM)

## Requirements

It's nice to know the following:

- React.js
- Basics of functional programming

## Help during the workshop

Here's a couple of useful resources that will help you during the workshop:

- [ClojureScript Synonyms](https://kanaka.github.io/clojurescript/web/synonym.html) — translation of common things from JavaScript into ClojureScript
- [ClojureScript Cheatsheet](http://cljs.info/cheatsheet/) — a quick reference to a standard library of the language
- [ClojureDocs](https://clojuredocs.org/) — documentation website
- [Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide) — a style guide to writing idiomatic Clojure code

## Agenda

- Intro into Lisp
- Intro into Clojure
- How to read Lisp code
- How to edit Lisp code
- Paredit and Parinfer editing modes
- Check setup
- Lectures & exercises

## Topics

- Primitive data types
- Variable declaration & local bindings
- Applying functions: Math operators
- Fighting parens: Threading macro
- Function declaration
- Control flow operators
- Data structures
- Operations on data structures
- Destructuring
- Higher-order functions and stdlib (?)
- JavaScript interop
- Multimethods (?)
- Namespaces
- Exploring example app
- Building your own app from scratch

## Setup

You have to be prepared for the workshop, so we don't have to waste time for setup

### Environment

- Install [Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- Install [Leiningen](https://leiningen.org/) `brew install leiningen` or using [other package manager](https://github.com/technomancy/leiningen/wiki/Packaging), [Windows installer](https://djpowell.github.io/leiningen-win-installer/)
- Initialize project: `lein new rc-cljs-workshop app`

### Editor

It's highly recommeneded to use _IntelliJ IDEA_ with _Cursive_ plugin since it has everything you'll need to start working with Clojure

#### IntelliJ IDEA

- Install Cursive plugin
- Configure Clojure REPL
- Enable Parinfer editing mode
- Check keybindings

#### Atom

Follow [this manual](https://gist.github.com/jasongilman/d1f70507bed021b48625). You don't have to install and configure everything, the important parts are: [Parinfer](https://github.com/oakmac/atom-parinfer) plugin, [language-clojure](https://gist.github.com/jasongilman/d1f70507bed021b48625#language-clojure) settings, [lisp-paredit](https://gist.github.com/jasongilman/d1f70507bed021b48625#lisp-paredit) settings and [Atom Settings](https://gist.github.com/jasongilman/d1f70507bed021b48625#atom-settings) sections.

## Useful links

- [Community Resources](http://clojure.org/community/resources)
- [ClojureScript REPL](http://jaredforsyth.com/reepl/)
- [ClojureScript Synonyms](https://kanaka.github.io/clojurescript/web/synonym.html)
- [ClojureScript Cheatsheet](http://cljs.info/cheatsheet/)
- [ClojureScript API](http://cljs.github.io/api/)
- [ClojureDocs](https://clojuredocs.org/)
- [The Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide)
- [Quickref for Clojure Core](https://clojuredocs.org/quickref)
- [ClojureScript Tutorial](https://www.niwi.nz/cljs-workshop/)
- [ClojureScript Koans](http://clojurescriptkoans.com/)
