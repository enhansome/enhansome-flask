# Awesome Flask with stars

> A curated list of awesome Flask resources and plugins

* [Awesome Flask](#awesome-flask)
  * [Framework](#framework)
  * [Admin interface](#admin-interface)
  * [Analytics](#analytics)
  * [Authentication](#authentication)
  * [Authorization](#authorization)
  * [Database](#database)
  * [Database Migrations](#database-migrations)
  * [Session](#session)
  * [Cache](#cache)
  * [Data Validation](#data-validation)
  * [Email](#email)
  * [i18n](#i18n)
  * [Full-text searching](#full-text-searching)
  * [Rate Limiting](#rate-limiting)
  * [Task Queue](#task-queue)
  * [Exception tracking](#exception-tracking)
  * [Tracing](#tracing)
  * [APM](#apm)
  * [Other SDK](#other-sdk)
  * [Frontend](#frontend)
  * [Development (Debugging/Testing/Documentation)](#development-debuggingtestingdocumentation)
  * [Utils](#utils)
* [Resources](#resources)
  * [Tutorials](#tutorials)
  * [Courses](#courses)
  * [Books](#books)
  * [Slides](#slides)
  * [Videos](#videos)
  * [Built with Flask](#built-with-flask)
  * [Boilerplate](#boilerplate)

## Framework

* [Zappa](https://github.com/Miserlou/Zappa) ⭐ 11,823 | 🐛 687 | 🌐 Python | 📅 2023-03-23 - Build and deploy server-less Flask applications on AWS Lambda and API Gateway
* [Flask-RESTful](https://github.com/flask-restful/flask-restful) ⭐ 6,916 | 🐛 146 | 🌐 Python | 📅 2024-07-19 - Simple framework for creating REST APIs
* [Eve](https://github.com/pyeve/eve) ⭐ 6,747 | 🐛 28 | 🌐 Python | 📅 2026-03-24 - REST API framework powered by Flask, MongoDB and good intentions
* [Connexion](https://github.com/zalando/connexion) ⭐ 4,608 | 🐛 186 | 🌐 Python | 📅 2026-08-03 - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation and OAuth2 support
* [Flask-RestPlus](https://github.com/noirbizarre/flask-restplus) ⭐ 2,731 | 🐛 370 | 🌐 Python | 📅 2023-03-22 - syntaxic sugar, helpers and automatically generated Swagger documentation.
* [Flask-Restless](https://github.com/jfinkels/flask-restless) ⭐ 1,004 | 🐛 111 | 🌐 Python | 📅 2020-05-16 - A Flask extension for creating simple ReSTful APIs from SQLAlchemy models
* [Flask-MongoRest](https://github.com/closeio/flask-mongorest) ⚠️ Archived - Restful API framework wrapped around MongoEngine
* [Flask-Potion](https://github.com/biosustain/potion) ⚠️ Archived - RESTful API framework for Flask and SQLAlchemy

## Admin interface

* [Flask-Admin](https://github.com/flask-admin/flask-admin) ⭐ 6,069 | 🐛 128 | 🌐 Python | 📅 2026-08-16 - Simple and extensible administrative interface framework for Flask

## Analytics

* [Flask-Analytics](https://github.com/citruspi/Flask-Analytics) ⭐ 82 | 🐛 2 | 🌐 Python | 📅 2016-10-12 - Analytics snippets generator extension for the Flask framework
* [Flask-Matomo](https://github.com/Lanseuo/flask-matomo) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2020-09-30 - Track requests to your Flask website with Matomo

## Authentication

* [Flask-Login](https://github.com/maxcountryman/flask-login) ⭐ 3,676 | 🐛 19 | 🌐 Python | 📅 2025-08-27 - Flask user session management
* [Flask-Security](https://github.com/mattupstate/flask-security) ⚠️ Archived - Quick and simple security for Flask applications
* [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) ⭐ 1,288 | 🐛 10 | 🌐 Python | 📅 2026-05-14 - Simple extension that provides Basic and Digest HTTP authentication for Flask routes
* [Flask-User](https://github.com/lingthio/Flask-User) ⭐ 1,073 | 🐛 124 | 🌐 Python | 📅 2022-02-03 - Customizable user account management for Flask
* [Flask-Praetorian](https://github.com/dusktreader/flask-praetorian) ⭐ 350 | 🐛 5 | 🌐 Python | 📅 2025-08-19 - Strong, Simple, and Precise security for Flask APIs (using jwt)

## Authorization

* [Authlib](https://github.com/lepture/authlib) ⭐ 5,400 | 🐛 140 | 🌐 Python | 📅 2026-08-11 - Authlib is an ambitious authentication library for OAuth 1, OAuth 2, OpenID clients, servers and more.
* [Authomatic](https://github.com/authomatic/authomatic) ⭐ 1,053 | 🐛 64 | 🌐 Python | 📅 2025-12-12 - Authomatic provides out of the box support for a number of providers using OAuth 1.0a (Twitter, Tumblr and more) and OAuth 2.0 (Facebook, Foursquare, GitHub, Google, LinkedIn, PayPal and more)
* [Flask-Dance](https://github.com/singingwolfboy/flask-dance) ⭐ 1,012 | 🐛 49 | 🌐 Python | 📅 2024-06-07 - OAuth consumer extension for Flask, shipped with pre-set support for Facebook, GitHub, Google, etc.
* [Flask-Pundit](https://github.com/anurag90x/flask-pundit) ⭐ 53 | 🐛 3 | 🌐 Python | 📅 2023-05-01 - Extension based on Rails' [Pundit](https://github.com/varvet/pundit) ⭐ 8,520 | 🐛 15 | 🌐 Ruby | 📅 2026-08-02 gem that provides easy way to organize access control for your models

## Database

* [Flask-SQLAlchemy](https://github.com/mitsuhiko/flask-sqlalchemy) ⭐ 4,311 | 🐛 38 | 🌐 Python | 📅 2026-05-18 - Adds SQLAlchemy support to Flask
* [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) ⭐ 831 | 🐛 45 | 🌐 Python | 📅 2024-01-18 - MongoEngine flask extension with WTF model forms support

## Database Migrations

* [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) ⭐ 2,404 | 🐛 1 | 🌐 Python | 📅 2026-05-14 - SQLAlchemy database migrations for Flask applications using Alembic

## Session

* [Flask-Session](https://github.com/fengsp/flask-session) ⭐ 534 | 🐛 36 | 🌐 Python | 📅 2025-06-14 - Server side session extension for Flask

## Cache

* [Flask-Caching](https://github.com/sh4nks/flask-caching) ⭐ 934 | 🐛 27 | 🌐 Python | 📅 2026-08-13 - Adds easy cache support to Flask
* [flask-heroku-cacheify](https://github.com/rdegges/flask-heroku-cacheify) ⭐ 41 | 🐛 2 | 🌐 Python | 📅 2018-09-26 - Automatic Flask cache configuration on Heroku

## Data Validation

* [Flask-WTF](https://github.com/lepture/flask-wtf) ⭐ 1,508 | 🐛 27 | 🌐 Python | 📅 2026-08-01 - Simple integration of Flask and WTForms, including CSRF, file upload and Recaptcha integration.

## Email

* [Flask-Mail](https://github.com/mattupstate/flask-mail/) ⭐ 642 | 🐛 26 | 🌐 Python | 📅 2026-06-10 - Flask-Mail adds SMTP mail sending to your Flask applications

## i18n

* [flask-babel](https://github.com/python-babel/flask-babel) ⭐ 452 | 🐛 20 | 🌐 Python | 📅 2024-08-07 - i18n and l10n support for Flask based on Babel and pytz

## Full-text searching

* [SQLAlchemy-Searchable](https://github.com/kvesteri/sqlalchemy-searchable) ⭐ 276 | 🐛 13 | 🌐 Python | 📅 2026-08-03 - Full-text searching for Flask-SQLAlchemy (Postgres only)
* [flask\_msearch](https://github.com/honmaple/flask-msearch) ⭐ 225 | 🐛 8 | 🌐 Python | 📅 2024-01-16 - Full text search for flask with whoosh

## Rate Limiting

* [Flask-Limiter](https://github.com/alisaifee/flask-limiter) ⭐ 1,204 | 🐛 6 | 🌐 Python | 📅 2026-05-10 - Flask-Limiter provides rate limiting features to flask routes

## Task Queue

* [celery](https://github.com/celery/celery/) ⭐ 28,788 | 🐛 801 | 🌐 Python | 📅 2026-08-16 - Distributed Task Queue
* [huey](https://github.com/coleifer/huey) ⭐ 6,004 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - a little task queue for python
* [Flask-Dramatiq](https://flask-dramatiq.rtfd.io/) - [dramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,310 | 🐛 60 | 🌐 Python | 📅 2026-08-13 integration for Flask applications.
* [Flask-RQ](https://github.com/mattupstate/flask-rq) ⭐ 235 | 🐛 1 | 🌐 Python | 📅 2026-07-15 - RQ (Redis Queue) integration for Flask applications

## Exception tracking

* [sentry-sdk](https://github.com/getsentry/sentry-python) ⭐ 2,202 | 🐛 446 | 🌐 Python | 📅 2026-08-15 - Python client for [Sentry](https://sentry.io/welcome/).
* [airbrake-python](https://github.com/airbrake/airbrake-python) ⭐ 52 | 🐛 14 | 🌐 Python | 📅 2022-09-12 - Python client for [Airbrake](https://airbrake.io/)

## Tracing

* [Flask-OpenTracing](https://github.com/opentracing-contrib/python-flask) ⭐ 138 | 🐛 9 | 🌐 Python | 📅 2026-04-22 - Distributed tracing with [OpenTracing](http://opentracing.io/).
* [flask-zipkin](https://github.com/qiajigou/flask-zipkin) ⭐ 40 | 🐛 10 | 🌐 Python | 📅 2024-05-06 - Distributed tracing with [Zipkin](https://zipkin.io/).

## APM

* [elastic-apm](https://github.com/elastic/apm-agent-python) ⭐ 430 | 🐛 141 | 🌐 Python | 📅 2026-08-15 - Elastic APM agent for Python

## Other SDK

* [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps) ⭐ 653 | 🐛 43 | 🌐 Python | 📅 2024-05-30 - Build and embed google maps in our Flask templates
* [Flask-Gravatar](https://github.com/zzzsochi/Flask-Gravatar) ⭐ 84 | 🐛 8 | 🌐 Python | 📅 2024-02-01 - Small and simple gravatar usage in Flask
* [Flask-Azure-Storage](https://github.com/alejoar/Flask-Azure-Storage) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2018-04-13 - Flask extension that provides integration with Azure Storage
* [Flask-Pusher](https://github.com/iurisilvio/Flask-Pusher) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2021-03-19 - Pusher integration for Flask

## Frontend

* [Flask-CORS](https://github.com/corydolphin/flask-cors) ⭐ 931 | 🐛 39 | 🌐 Python | 📅 2026-06-09 - A Flask extension for handling Cross Origin Resource Sharing (CORS), making cross-origin AJAX possible
* [flask-assets](https://github.com/miracle2k/flask-assets) ⭐ 460 | 🐛 22 | 🌐 Python | 📅 2023-12-15 - Flask webassets integration
* [flask-s3](https://github.com/e-dard/flask-s3) ⭐ 200 | 🐛 19 | 🌐 Python | 📅 2023-08-26 - Seamlessly serve your static assets of your Flask app from Amazon S3
* [Flask-HTMLmin](https://github.com/hamidfzm/Flask-HTMLmin) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2025-01-05 - Flask html minifier
* [Flask-SSLify](https://github.com/kennethreitz/flask-sslify) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2022-09-15 - Force SSL on your Flask app

## Development (Debugging/Testing/Documentation)

* [connexion](https://github.com/zalando/connexion) ⭐ 4,608 | 🐛 186 | 🌐 Python | 📅 2026-08-03 - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation & OAuth2 support.
* [Flasgger](https://github.com/rochacbruno/flasgger) ⭐ 3,741 | 🐛 286 | 🌐 Python | 📅 2024-06-17 - Create API documentation for Flask views using Swagger 2.0 specs
* [nplusone](https://github.com/jmcarp/nplusone#flask-sqlalchemy) ⭐ 1,068 | 🐛 24 | 🌐 Python | 📅 2022-11-25 - Auto-detect n+1 queries with Flask and SQLAlchemy
* [Flask-DebugToolbar](https://github.com/mgood/flask-debugtoolbar) ⭐ 978 | 🐛 43 | 🌐 JavaScript | 📅 2026-08-03 - A port of the django debug toolbar to flask
* [Flask-MonitoringDashboard](https://github.com/flask-dashboard/Flask-MonitoringDashboard) ⭐ 827 | 🐛 74 | 🌐 Python | 📅 2026-06-29 - Automatically monitor the evolving performance of Flask/Python web services.
* [flask\_profiler](https://github.com/muatik/flask-profiler) ⭐ 753 | 🐛 44 | 🌐 Python | 📅 2022-12-02 - endpoint analyzer/profiler for Flask
* [flask-apispec](https://github.com/jmcarp/flask-apispec) ⭐ 653 | 🐛 116 | 🌐 Python | 📅 2025-05-04 - simple self-documenting APIs with flask
* [Flask-Testing](https://github.com/jarus/flask-testing) ⭐ 501 | 🐛 54 | 🌐 Python | 📅 2023-08-21 - Unittest extensions for Flask
* [pytest-flask](https://github.com/pytest-dev/pytest-flask) ⭐ 499 | 🐛 13 | 🌐 Python | 📅 2026-08-14 - A set of pytest fixtures to test Flask applications
* [flask2postman](https://github.com/numberly/flask2postman) ⭐ 146 | 🐛 5 | 🌐 Python | 📅 2022-09-15 - Generate a Postman collection from your Flask application
* [flask-debug-toolbar-mongo](https://github.com/cenkalti/flask-debug-toolbar-mongo) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2017-02-04 - MongoDB panel for the Flask Debug Toolbar

## Utils

* [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) ⭐ 5,508 | 🐛 7 | 🌐 Python | 📅 2026-07-30 - Socket.IO integration for Flask applications
* [Flask-graphql](https://github.com/graphql-python/flask-graphql) ⭐ 1,338 | 🐛 41 | 🌐 Python | 📅 2023-01-03 - Adds GraphQL support to your Flask application
* [Mixer](https://github.com/klen/mixer) ⭐ 955 | 🐛 49 | 🌐 Python | 📅 2024-03-08 - Mixer is application to generate instances of Django or SQLAlchemy models
* [flask-marshmallow](https://github.com/marshmallow-code/flask-marshmallow) ⭐ 887 | 🐛 25 | 🌐 Python | 📅 2026-08-03 Flask + marshmallow for beautiful APIs
* [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) ⭐ 380 | 🐛 1 | 🌐 Python | 📅 2026-05-14 - Formatting of dates and times in Flask templates using moment.js
* [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) ⭐ 327 | 🐛 12 | 🌐 Python | 📅 2026-04-22 - Flask-Bcrypt is a Flask extension that provides bcrypt hashing utilities for your application
* [flask-jsonrpc](https://github.com/cenobites/flask-jsonrpc) ⭐ 292 | 🐛 12 | 🌐 Python | 📅 2026-08-10 - A basic JSON-RPC implementation for your Flask-powered sites
* [Flask-Paginate](https://github.com/lixxu/flask-paginate) ⭐ 287 | 🐛 10 | 🌐 Python | 📅 2024-12-23 - Pagination support for Flask
* [Flask-FeatureFlags](https://github.com/trustrachel/Flask-FeatureFlags) ⚠️ Archived - A Flask extension that enables or disables features based on configuration
* [Flask-Reggie](https://github.com/rhyselsmore/flask-reggie) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2013-07-08 - Regex Converter for Flask URL Routes

# Resources

## Tutorials

* [Discover Flask - Full Stack Web Development with Flask](https://github.com/realpython/discover-flask) ⭐ 4,547 | 🐛 6 | 🌐 Python | 📅 2020-09-30
* [Flaskr - Intro to Flask, Test Driven Development, and jQuery](https://github.com/mjhea0/flaskr-tdd) ⭐ 2,342 | 🐛 17 | 🌐 Python | 📅 2026-04-13
* [How to build a news app that never goes down and costs you practically nothing](http://blog.apps.npr.org/2013/02/14/app-template-redux.html) (by NPR)
* [Building websites in Python with Flask](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/)
* [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
* [Implementing a RESTful Web API with Python & Flask](http://blog.luisrei.com/articles/flaskrest.html)

## Courses

* [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088)
* [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388)

## Books

* [Explore Flask](https://exploreflask.com/en/latest/)
* [Flask Web Development](http://shop.oreilly.com/product/0636920031116.do)
* [Real Python](https://realpython.com)
* [Learning Flask Framework](https://www.packtpub.com/web-development/learning-flask-framework)
* [Flask Blueprints](https://www.packtpub.com/web-development/flask-blueprints)
* [Flask Framework Cookbook](https://www.packtpub.com/web-development/flask-framework-cookbook)
* [Mastering Flask](https://www.packtpub.com/web-development/mastering-flask)
* [Building Web Applications with Flask](https://www.packtpub.com/web-development/building-web-applications-flask)

## Slides

* [Creating beautiful REST APIs with Flask](http://pycoder.net/bospy/presentation.html)
* [Advanced Flask Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns)
* [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness)
* [Domain Driven Design (... with Flask)](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask)
* [In Flask we Trust](https://speakerdeck.com/playpauseandstop/in-flask-we-trust)

## Videos

* [PyVideo](https://pyvideo.org/search.html?q=flask)
* [Practical Flask Web Development Tutorials](https://www.youtube.com/playlist?list=PLQVvvaa0QuDc_owjTbIY4rbgXOFkUYOUB)

## Built with Flask

* [airflow](https://github.com/apache/incubator-airflow) ⭐ 46,508 | 🐛 1,880 | 🌐 Python | 📅 2026-08-16 - Airflow is a system to programmatically author, schedule and monitor data pipelines.
* [security\_monkey](https://github.com/Netflix/security_monkey) ⚠️ Archived - monitors policy changes and alerts on insecure configurations in an AWS account.
* [securedrop](https://github.com/freedomofpress/securedrop) ⭐ 3,872 | 🐛 459 | 🌐 Python | 📅 2026-08-16- an open-source whistleblower submission system that media organizations can use to securely accept documents from and communicate with anonymous sources.
* [sync\_engine](https://github.com/nylas/sync-engine) ⚠️ Archived - IMAP/SMTP sync system with modern APIs
* [timesketch](https://github.com/google/timesketch) ⭐ 3,391 | 🐛 217 | 🌐 Python | 📅 2026-08-09 - Collaborative forensics timeline analysis
* [flaskbb](https://github.com/flaskbb/flaskbb) ⭐ 2,660 | 🐛 16 | 🌐 Python | 📅 2026-08-11 - A classic Forum Software in Python using Flask.
* [Quokka CMS](https://github.com/rochacbruno/quokka) ⚠️ Archived - CMS made with Flask and MongoDB
* [indico](https://github.com/indico/indico) ⭐ 2,099 | 🐛 887 | 🌐 Python | 📅 2026-08-14 - a general-purpose event management web-based solution. It includes a full-blown conference organization workflow as well as tools for meeting management and room booking. It provides as well integration with video-conferencing solutions.
* [overholt](https://github.com/mattupstate/overholt) ⚠️ Archived - Example Flask application illustrating common practices
* [June](https://github.com/pythoncn/june) ⚠️ Archived - ~~python-china.org~~
* [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) ⭐ 798 | 🐛 13 | 🌐 Python | 📅 2024-11-12 - Freezes a Flask application into a set of static files
* [changes](https://github.com/dropbox/changes) ⚠️ Archived - A dashboard for your code. A build system.
* [thepast.me](https://github.com/laiwei/thepast) ⚠️ Archived
* [pypress](https://github.com/laoqiu/pypress) ⭐ 547 | 🐛 5 | 🌐 Python | 📅 2020-03-28 - flask team blog
* [Skylines](https://github.com/skylines-project/skylines) ⭐ 407 | 🐛 107 | 🌐 Python | 📅 2026-08-14 - Live tracking, flight database and competition framework
* [redispapa](https://github.com/no13bus/redispapa) ⭐ 394 | 🐛 12 | 🌐 TypeScript | 📅 2026-04-16 - another redis monitor by using flask, angular, socket.io
* [chat](https://github.com/lzyy/chat) ⭐ 326 | 🐛 5 | 🌐 Python | 📅 2022-09-15 - a live chat built with python (flask + gevent + apscheduler) + redis
* \[PythonBuddy] (<https://github.com/ethanchewy/PythonBuddy> ⭐ 282 | 🐛 17 | 🌐 Python | 📅 2026-02-20) - Online Python Editor With Live Syntax Checking and Execution
* [flaskblog](https://github.com/defshine/flaskblog) ⭐ 179 | 🐛 1 | 🌐 CSS | 📅 2017-04-18 - a simple blog system based on flask
* [Zerqu](https://github.com/lepture/zerqu) ⭐ 173 | 🐛 2 | 🌐 Python | 📅 2020-03-28 - ZERQU is a content-focused API-based platform. eg: [Python-China](https://python-china.org)
* [cleanblog](https://github.com/defshine/cleanblog) ⭐ 109 | 🐛 4 | 🌐 JavaScript | 📅 2016-12-10 - a clean blog system based on flask and mongoengine
* [mcflyin](https://github.com/wrobstory/mcflyin) ⭐ 86 | 🐛 1 | 🌐 Python | 📅 2022-09-16 - A small timeseries transformation API built on Flask and Pandas
* [thenewsmeme.com](https://github.com/danjac/newsmeme) ⚠️ Archived
* [GuitarFan](https://github.com/lowrain/GuitarFan) ⭐ 50 | 🐛 3 | 🌐 JavaScript | 📅 2020-03-28 - guitar tab
* [cleansweep](https://github.com/AamAadmiParty/cleansweep) ⭐ 41 | 🐛 40 | 🌐 JavaScript | 📅 2020-03-28 - Volunteer & Campaign Management System
* [motiky](https://github.com/notedit/motiky) ⭐ 39 | 🐛 0 | 📅 2013-06-26
* [missing](https://github.com/notedit/missing) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2013-01-26 - a list service called missing
* [zmusic-ng](https://git.zx2c4.com/zmusic-ng/) - ZX2C4 Music provides a web interface for playing and downloading music files using metadata.
* [chatapp](https://github.com/vinceprignano/chatapp) - Flask and Angular.js Chat Application using Socket.io

## Boilerplate

* [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) ⭐ 4,958 | 🐛 268 | 🌐 Python | 📅 2026-07-10 - Simple and rapid application builder framework, built on top of Flask. includes detailed security, auto form generation, google charts and much more
* [cookiecutter-flask](https://github.com/sloria/cookiecutter-flask) ⭐ 4,723 | 🐛 24 | 🌐 Python | 📅 2025-12-02
* [fbone](https://github.com/imwilsonxu/fbone) ⭐ 1,702 | 🐛 24 | 🌐 Python | 📅 2022-05-17
* [Flask-Foundation](https://github.com/JackStouffer/Flask-Foundation) ⭐ 1,277 | 🐛 3 | 🌐 Python | 📅 2023-05-01
* [flask-rest-template](https://github.com/alexandre/flask-rest-template) ⭐ 110 | 🐛 3 | 🌐 Python | 📅 2022-11-16
* [gae-init](https://gae-init.appspot.com) - Flask boilerplate running on Google App Engine

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
