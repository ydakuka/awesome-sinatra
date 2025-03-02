# Awesome Sinatra

> A curated list of awesome things related to Sinatra [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme)

## Table of Contents

- [General](#general)
- [Generators](#generators)
- [Authentication](#authentication)
- [Boilerplate and Template](#boilerplate-and-template)
- [Concurrency](#concurrency)
- [CMS](#cms)
- [File Uploading](#file-uploading)
- [Micro Frameworks inspired by Sinatra](#micro-frameworks-inspired-by-sinatra)
- [NoSQL](#nosql)
- [ORM](#orm)
- [Routers](#routers)
- [Views](#views)
- [Validation & Type Coercion](#validation--type-coercion)
- [Middleware](#middleware)
- [Security](#security)
- [Service Integration](#service-integration)
- [Server Side Rendering](#server-side-rendering)
- [Stylesheets](#stylesheets)
- [Testing](#testing)
- [Writing APIs](#writing-apis)

## General

* [Sinatra](https://sinatrarb.com/) - Sinatra Official website.
* [Sinatra on Github](https://github.com/sinatra/sinatra)
* [Sinatra Recipes](https://github.com/sinatra/sinatra-recipes) - Community contributed recipes and techniques.
* [Sinatra - The Book](https://github.com/sinatra/sinatra-book) - A cookbook full of excellent tutorials
  and recipes for developing Sinatra web applications.
* [Sinatra in the wild](https://github.com/sinatra/sinatra.github.com/blob/main/wild.markdown) - Various
  applications, extensions and websites built with Sinatra.

## Generators

* [corneal](https://github.com/thebrianemory/corneal) - A Sinatra app generator with Rails-like simplicity.
* [sinator](https://github.com/kuntoaji/sinator) - Sinatra application generator.
* [hoboken](https://github.com/bnadlerjr/hoboken) - Sinatra project generator and templates.

## Authentication

* [sinatra_warden](https://github.com/wardencommunity/sinatra_warden) - Authentication module for sinatra and some auth helpers.
* [doorkeeper](https://github.com/doorkeeper-gem/doorkeeper) - Doorkeeper is an OAuth 2 provider.
* [sinatra_omniauth](https://github.com/cjheath/sinatra_omniauth) - A Sinatra extension that provides pure OmniAuth goodness
  to your application (with DataMapper).

## Boilerplate and Template

* [sinatra-bootstrap](https://github.com/bootstrap-ruby/sinatra-bootstrap) - A demonstrator for Sinatra and Twitter's Bootstrap.
* [sinatra_boilerplate](https://github.com/reedstonefood/sinatra_boilerplate) - Basic template Sinatra website, with Twitter Bootstrap and ActiveRecord.
* [sinatras-skeleton](https://github.com/simonneutert/sinatras-skeleton) - Basic Sinatra Skeleton MVC CRUD App with Sprockets, Warden, ActiveRecord and PostgreSQL.
* [scoop](https://github.com/abhinavs/scoop) - A production-ready Sinatra boilerplate project using Corneal, ActiveRecord, Capistrano, Puma & Nginx.
* [sinatra-activerecord-starter-kit](https://github.com/LaunchAcademy/sinatra-activerecord-starter-kit) - Sinatra Active Record Starter Kit.

## Concurrency

- [async_sinatra](https://github.com/raggi/async_sinatra) - A plugin for Sinatra to provide a DSL extension
  for using Thin for asynchronous responses.

## CMS

* [nesta](https://github.com/gma/nesta) - A lightweight CMS, implemented in Sinatra. Content can be written
  in Markdown or Textile and stored in text file

## File Uploading

* [carrierwave](https://github.com/carrierwaveuploader/carrierwave) - A classier solution for file uploads for Rails,
  Sinatra and other Ruby web frameworks.

## Micro Frameworks inspired by Sinatra

* [nancy](https://github.com/guilleiguaran/nancy) - Minimal Ruby microframework for web development inspired in Sinatra and Cuba.
* [padrino](https://github.com/padrino/padrino-framework) - Padrino is a full-stack ruby framework built upon Sinatra.
* [rack::app](https://github.com/rack-app/rack-app) - Minimalist framework for building rack applications.
* [scorched](https://github.com/wardrop/scorched) - Light-weight, DRY as a desert, web framework for Ruby.

## NoSQL

> Key-value

* [redis-sinatra](https://github.com/redis-store/redis-sinatra) - Redis stores for Sinatra.
* [redis_dashboard](https://github.com/BaseSecrete/redis_dashboard) - Sinatra app to monitor Redis servers.

## ORM

* [sinatra-activerecord](https://github.com/sinatra-activerecord/sinatra-activerecord) - Extends Sinatra with ActiveRecord helper methods and Rake tasks.
* [otr-activerecord](https://github.com/jhollinger/otr-activerecord) - Off The Rails: Use ActiveRecord with Grape, Sinatra, Rack, or anything else!

## Routers

* [sinatra-router](https://github.com/brandur/sinatra-router) - A tiny vendorable router that makes it 
  easy to try routes from a number of different modular Sinatra applications.
* [sinatra-subdomain](https://github.com/fnando/sinatra-subdomain) - Separate routes for subdomains in Sinatra apps.
* [yard-sinatra](https://github.com/rkh/yard-sinatra) - Display sinatra routes in yard documentation.
* [sinatra-mapping](https://github.com/hallison/sinatra-mapping) - Sinatra::Mapping extension is a minimal module that is useful
  for create map names for Sinatra web application.

## Views

* [sinatra-partial](https://github.com/yb66/Sinatra-Partial) - Partials for Sinatra!
* [kaminari-sinatra](https://github.com/kaminari/kaminari-sinatra) - Kaminari Sinatra adapter.
* [sinatra-flash](https://github.com/SFEley/sinatra-flash) - Flash messages for the Sinatra.
* [sinatra-redirect-with-flash](https://github.com/vast/sinatra-redirect-with-flash) - Provides redirect helper
  that can set proper flash before the redirection.

## Validation & Type Coercion

* [sinatra-param](https://github.com/mattt/sinatra-param) - Parameter Validation & Type Coercion for Sinatra.

## Middleware

* [amnesia](https://github.com/benschwarz/amnesia) - A Sinatra rack middleware that presents memcached server stats.
* [rack_csrf](https://github.com/baldowl/rack_csrf) - Anti-CSRF Rack middleware.
* [rack-insight](https://github.com/pboling/rack-insight) - Debugging toolbar for Rack applications implemented as middleware.

## Security

* [encrypted_cookie](https://github.com/cvonkleist/encrypted_cookie) - AES-128 encrypted session cookies for Rack (and Sinatra and other frameworks).

## Service Integration

> Slack

* [snarkov](https://github.com/gesteves/snarkov) - A hilarious Sinatra-based Markov bot for Slack.

> MISC

* [shopify-sinatra-app](https://github.com/kevinhughes27/shopify-sinatra-app) - Lightweight extension for
  building Shopify apps using Sinatra.

## Server Side Rendering

* [react-sinatra](https://github.com/namusyaka/react-sinatra) - React on Sinatra Integration, Server Side Rendering.

## Stylesheets

* [sinatra-asset-pipeline](https://github.com/kalasjocke/sinatra-asset-pipeline) - An asset pipeline for Sinatra based on Sprockets.
* [sprockets-helpers](https://github.com/petebrowne/sprockets-helpers) - Asset path helpers for Sprockets 2.0 applications.

## Testing

* [mock_server](https://github.com/mvemjsun/mock_server) - A lightweight Sinatra application backed by sqlite that can mock ReST responses.
  Has interface to easily create, search & maintain mocks. No need to program mocks into a language specific implementation.
* [rack-test](https://github.com/rack/rack-test) - Rack::Test is a small, simple testing API for Rack apps.

## Writing APIs

* [Pliny](https://github.com/interagent/pliny) - An opinionated toolkit for writing excellent APIs in Ruby.
* [sinatra-jsonp](https://github.com/shtirlic/sinatra-jsonp) - JSONP output helper for Sinatra.
* [sinatra-rest-api](https://github.com/blocknotes/sinatra-rest-api) - Sinatra REST API generator.
* [sinja](https://github.com/mwpastore/sinja) - RESTful, {json:api}-compliant web services in Sinatra.
