# Awesome Flask with stars

> A micro web framework for Python and the extension ecosystem around it.

Tutorials, talks, and videos on this list are free. Paid courses are not accepted.

<p align="right">
  <a href="https://flask.palletsprojects.com/">
    <img src="flask-icon.svg" width="72" alt="Flask">
  </a>
</p>

## Contents

* [Official Resources](#official-resources)
* [Extensions](#extensions)
  * [Admin](#admin)
  * [APIs](#apis)
  * [Auth](#auth)
  * [Cache](#cache)
  * [Databases](#databases)
  * [Developer Tools](#developer-tools)
  * [Email](#email)
  * [Forms and Validation](#forms-and-validation)
  * [Full-text Search](#full-text-search)
  * [Security](#security)
  * [Task Queues](#task-queues)
  * [Utils](#utils)
* [Resources](#resources)
  * [Community](#community)
  * [Tutorials](#tutorials)
  * [Books](#books)
  * [Talks](#talks)
  * [Videos](#videos)
* [Projects](#projects)
  * [Boilerplates](#boilerplates)
  * [Open Source Projects](#open-source-projects)
* [Hosting](#hosting)

## Official Resources

* [Source Code](https://github.com/pallets/flask) ⭐ 72,145 | 🐛 3 | 🌐 Python | 📅 2026-08-16 - Flask itself, hosted by Pallets.
* [Quart](https://github.com/pallets/quart) ⭐ 3,658 | 🐛 27 | 🌐 Python | 📅 2026-08-25 - Official ASGI counterpart of Flask, with a compatible API.
* [Flask](https://flask.palletsprojects.com/) - Official documentation for current and past releases.
* [Flaskr Tutorial](https://flask.palletsprojects.com/tutorial/) - Official tutorial that builds a small blog.
* [Pallets-Eco](https://github.com/pallets-eco) - Community extensions maintained next to the core projects.

## Extensions

### Admin

* [Flask-Admin](https://github.com/pallets-eco/flask-admin) ⭐ 6,071 | 🐛 128 | 🌐 Python | 📅 2026-08-16 - Extensible admin interface for managing application data.

### APIs

* [Flask-RESTful](https://github.com/flask-restful/flask-restful) ⭐ 6,915 | 🐛 145 | 🌐 Python | 📅 2024-07-19 - Lightweight helpers for building REST APIs.
* [Eve](https://github.com/pyeve/eve) ⭐ 6,748 | 🐛 29 | 🌐 Python | 📅 2026-03-24 - REST API framework powered by Flask and MongoDB.
* [Connexion](https://github.com/spec-first/connexion) ⭐ 4,611 | 🐛 185 | 🌐 Python | 📅 2026-08-03 - Spec-first OpenAPI framework that can run on Flask.
* [Flasgger](https://github.com/flasgger/flasgger) ⭐ 3,744 | 🐛 286 | 🌐 Python | 📅 2024-06-17 - OpenAPI and Swagger UI for Flask views.
* [Flask-RESTX](https://github.com/python-restx/flask-restx) ⭐ 2,235 | 🐛 322 | 🌐 Python | 📅 2026-04-14 - Community fork of Flask-RESTPlus with Swagger documentation.
* [APIFlask](https://github.com/apiflask/apiflask) ⭐ 1,135 | 🐛 36 | 🌐 Python | 📅 2026-08-23 - Flask web API framework with marshmallow validation and OpenAPI generation.
* [flask-smorest](https://github.com/marshmallow-code/flask-smorest) ⭐ 719 | 🐛 59 | 🌐 Python | 📅 2026-08-03 - Marshmallow-first REST framework with automatic OpenAPI.
* [Flask-Rebar](https://github.com/plangrid/flask-rebar) ⭐ 235 | 🐛 54 | 🌐 Python | 📅 2026-08-27 - Flask, marshmallow, and OpenAPI combined for REST services.

### Auth

* [Authlib](https://github.com/authlib/authlib) ⭐ 5,407 | 🐛 142 | 🌐 Python | 📅 2026-08-27 - OAuth 1, OAuth 2, and OpenID Connect clients and servers.
* [Flask-Login](https://github.com/maxcountryman/flask-login) ⭐ 3,675 | 🐛 19 | 🌐 Python | 📅 2025-08-27 - Session-based user login management.
* [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended) ⭐ 1,581 | 🐛 18 | 🌐 Python | 📅 2026-08-20 - JWT authentication with refresh tokens and fine-grained claims.
* [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) ⭐ 1,289 | 🐛 10 | 🌐 Python | 📅 2026-05-14 - Basic, digest, and token authentication for routes.
* [Flask-User](https://github.com/lingthio/Flask-User) ⭐ 1,075 | 🐛 124 | 🌐 Python | 📅 2022-02-03 - Customizable user registration, login, and account management.
* [Authomatic](https://github.com/authomatic/authomatic) ⭐ 1,053 | 🐛 64 | 🌐 Python | 📅 2025-12-12 - Framework-agnostic OAuth and OpenID client.
* [Flask-Dance](https://github.com/singingwolfboy/flask-dance) ⭐ 1,012 | 🐛 49 | 🌐 Python | 📅 2024-06-07 - OAuth consumer with built-in providers such as GitHub and Google.
* [Flask-Security](https://github.com/pallets-eco/flask-security) ⭐ 698 | 🐛 8 | 🌐 Python | 📅 2026-08-27 - Account management, authentication, and authorization. Continues Flask-Security-Too.
* [Flask-Session](https://github.com/pallets-eco/flask-session) ⭐ 534 | 🐛 36 | 🌐 Python | 📅 2025-06-14 - Server-side sessions for Flask.
* [Flask-Praetorian](https://github.com/dusktreader/flask-praetorian) ⭐ 350 | 🐛 5 | 🌐 Python | 📅 2025-08-19 - JWT authentication and role-based authorization for APIs.
* [Flask-Pundit](https://github.com/anurag90x/flask-pundit) ⭐ 53 | 🐛 3 | 🌐 Python | 📅 2023-05-01 - Policy-based authorization inspired by Rails Pundit.

### Cache

* [Flask-Caching](https://github.com/pallets-eco/flask-caching) ⭐ 934 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - Caching support with multiple backends.

### Databases

* [Flask-SQLAlchemy](https://github.com/pallets-eco/flask-sqlalchemy) ⭐ 4,309 | 🐛 38 | 🌐 Python | 📅 2026-05-18 - SQLAlchemy integration for Flask.
* [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) ⭐ 2,404 | 🐛 1 | 🌐 Python | 📅 2026-05-14 - Database migrations for Flask-SQLAlchemy via Alembic.
* [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) ⭐ 831 | 🐛 45 | 🌐 Python | 📅 2024-01-18 - MongoEngine integration with WTForms support.
* [Advanced Alchemy](https://github.com/litestar-org/advanced-alchemy) ⭐ 798 | 🐛 56 | 🌐 Python | 📅 2026-08-17 - SQLAlchemy companion with repositories, Alembic helpers, and a first-party Flask extension.
* [Flask-PyMongo](https://github.com/mongodb-labs/flask-pymongo) ⭐ 720 | 🐛 7 | 🌐 Python | 📅 2026-08-26 - PyMongo integration for MongoDB.
* [Flask-Alembic](https://github.com/pallets-eco/flask-alembic) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2025-11-17 - Alembic migrations wired to a Flask-SQLAlchemy database.

### Developer Tools

* [Sentry](https://github.com/getsentry/sentry-python) ⭐ 2,201 | 🐛 424 | 🌐 Python | 📅 2026-08-28 - Error tracking SDK with a Flask integration.
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-python-contrib) ⭐ 1,089 | 🐛 652 | 🌐 Python | 📅 2026-08-27 - Tracing and metrics instrumentation, including Flask.
* [nplusone](https://github.com/jmcarp/nplusone) ⭐ 1,068 | 🐛 24 | 🌐 Python | 📅 2022-11-25 - Detects N+1 queries when using Flask-SQLAlchemy.
* [Flask-DebugToolbar](https://github.com/pallets-eco/flask-debugtoolbar) ⭐ 979 | 🐛 43 | 🌐 JavaScript | 📅 2026-08-03 - In-browser debug toolbar, ported from Django.
* [Mixer](https://github.com/klen/mixer) ⭐ 954 | 🐛 49 | 🌐 Python | 📅 2024-03-08 - Object factory for SQLAlchemy and Django models.
* [Flask-MonitoringDashboard](https://github.com/flask-dashboard/Flask-MonitoringDashboard) ⭐ 827 | 🐛 74 | 🌐 Python | 📅 2026-06-29 - Automatic performance monitoring for Flask services.
* [Flask-Testing](https://github.com/jarus/flask-testing) ⭐ 501 | 🐛 54 | 🌐 Python | 📅 2023-08-21 - Unittest helpers for Flask applications.
* [pytest-flask](https://github.com/pytest-dev/pytest-flask) ⭐ 499 | 🐛 13 | 🌐 Python | 📅 2026-08-24 - Pytest fixtures for Flask applications.
* [Elastic APM](https://github.com/elastic/apm-agent-python) ⭐ 431 | 🐛 140 | 🌐 Python | 📅 2026-08-27 - Application performance monitoring for Flask.

### Email

* [Flask-Mail](https://github.com/pallets-eco/flask-mail) ⭐ 642 | 🐛 26 | 🌐 Python | 📅 2026-06-10 - SMTP email sending for Flask.
* [Flask-Mailman](https://github.com/waynerv/flask-mailman) ⭐ 129 | 🐛 7 | 🌐 Python | 📅 2024-09-04 - Port of Django's mail system to Flask.

### Forms and Validation

* [Flask-WTF](https://github.com/pallets-eco/flask-wtf) ⭐ 1,508 | 🐛 29 | 🌐 Python | 📅 2026-08-01 - WTForms integration with CSRF, file upload, and reCAPTCHA.
* [Flask-Marshmallow](https://github.com/marshmallow-code/flask-marshmallow) ⭐ 887 | 🐛 25 | 🌐 Python | 📅 2026-08-03 - Marshmallow integration for serialization and validation.
* [Flask-Pydantic](https://github.com/pallets-eco/flask-pydantic) ⭐ 435 | 🐛 22 | 🌐 Python | 📅 2025-12-22 - Pydantic validation for Flask views.

### Full-text Search

* [SQLAlchemy-Searchable](https://github.com/falcony-io/sqlalchemy-searchable) ⭐ 276 | 🐛 13 | 🌐 Python | 📅 2026-08-03 - Full-text search for SQLAlchemy models on PostgreSQL.
* [flask-msearch](https://github.com/honmaple/flask-msearch) ⭐ 225 | 🐛 8 | 🌐 Python | 📅 2024-01-16 - Full-text search for Flask, with Whoosh support.

### Security

* [Flask-Limiter](https://github.com/alisaifee/flask-limiter) ⭐ 1,204 | 🐛 6 | 🌐 Python | 📅 2026-05-10 - Rate limiting for Flask routes.
* [Flask-CORS](https://github.com/corydolphin/flask-cors) ⭐ 932 | 🐛 40 | 🌐 Python | 📅 2026-06-09 - Cross-Origin Resource Sharing (CORS) support.
* [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) ⭐ 327 | 🐛 12 | 🌐 Python | 📅 2026-04-22 - Bcrypt password hashing.
* [Flask-SeaSurf](https://github.com/maxcountryman/flask-seasurf) ⭐ 195 | 🐛 20 | 🌐 Python | 📅 2025-09-04 - CSRF protection for Flask.
* [Flask-Talisman](https://github.com/wntrblm/flask-talisman) ⭐ 87 | 🐛 6 | 🌐 Python | 📅 2024-04-17 - HTTPS enforcement and security headers.

### Task Queues

* [Celery](https://github.com/celery/celery) ⭐ 28,830 | 🐛 754 | 🌐 Python | 📅 2026-08-27 - Distributed task queue commonly used with Flask.
* [Huey](https://github.com/coleifer/huey) ⭐ 6,014 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - Small Redis-backed task queue.
* [Dramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,309 | 🐛 63 | 🌐 Python | 📅 2026-08-13 - Fast alternative to Celery, with [Flask-Dramatiq](https://flask-dramatiq.readthedocs.io/) available.
* [Flask-RQ](https://github.com/pallets-eco/flask-rq) ⭐ 235 | 🐛 1 | 🌐 Python | 📅 2026-07-15 - Redis Queue (RQ) integration for Flask and Quart.

### Utils

* [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) ⭐ 5,508 | 🐛 7 | 🌐 Python | 📅 2026-07-30 - Socket.IO integration for Flask.
* [flask-graphql](https://github.com/graphql-python/flask-graphql) ⭐ 1,339 | 🐛 41 | 🌐 Python | 📅 2023-01-03 - GraphQL support for Flask.
* [Frozen-Flask](https://github.com/Frozen-Flask/Frozen-Flask) ⭐ 797 | 🐛 13 | 🌐 Python | 📅 2024-11-12 - Freezes a Flask app into a static site.
* [Flask-GoogleMaps](https://github.com/flask-extensions/Flask-GoogleMaps) ⭐ 654 | 🐛 43 | 🌐 Python | 📅 2024-05-30 - Embed Google Maps in Flask templates.
* [Flask-Assets](https://github.com/miracle2k/flask-assets) ⭐ 460 | 🐛 22 | 🌐 Python | 📅 2023-12-15 - Webassets integration for bundling and minifying static files.
* [Flask-Babel](https://github.com/python-babel/flask-babel) ⭐ 452 | 🐛 20 | 🌐 Python | 📅 2024-08-07 - Internationalization and localization via Babel.
* [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) ⭐ 381 | 🐛 1 | 🌐 Python | 📅 2026-05-14 - Moment.js helpers for dates in Jinja templates.
* [flask-jsonrpc](https://github.com/cenobites/flask-jsonrpc) ⭐ 292 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - JSON-RPC support for Flask.
* [Flask-Paginate](https://github.com/lixxu/flask-paginate) ⭐ 288 | 🐛 10 | 🌐 Python | 📅 2024-12-23 - Pagination helpers for Flask.
* [flask-s3](https://github.com/e-dard/flask-s3) ⭐ 200 | 🐛 19 | 🌐 Python | 📅 2023-08-26 - Serve Flask static assets from Amazon S3.
* [Flask-HTMLmin](https://github.com/hamidfzm/Flask-HTMLmin) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2025-01-05 - HTML minification for Flask responses.

## Resources

### Community

* [Discord](https://discord.gg/pallets) - Pallets community server. Use the Flask help channels.
* [Reddit](https://www.reddit.com/r/flask/) - Flask subreddit.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/flask) - Questions tagged `flask`.

### Tutorials

* [Discover Flask](https://github.com/realpython/discover-flask) ⭐ 4,547 | 🐛 6 | 🌐 Python | 📅 2020-09-30 - Full-stack Flask series from Real Python.
* [Flaskr TDD](https://github.com/mjhea0/flaskr-tdd) ⭐ 2,343 | 🐛 17 | 🌐 Python | 📅 2026-04-13 - Introduction to Flask, test-driven development, and JavaScript.
* [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) - Long-form series covering a full Flask application.

### Books

* [Explore Flask](https://explore-flask.readthedocs.io/en/latest/) - Free book on Flask patterns and project structure.
* [Flask Web Development](https://www.oreilly.com/library/view/flask-web-development/9781491991725/) - O'Reilly book by Miguel Grinberg that builds a real application.

### Talks

* [Advanced Flask Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns) - Patterns from Armin Ronacher.
* [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness) - Talk by Kenneth Reitz.
* [Domain Driven Design with Flask](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask) - Applying DDD ideas in Flask.

### Videos

* [PyVideo](https://pyvideo.org/search.html?q=flask) - Conference talks tagged Flask.
* [Python Flask Tutorial](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH) - Full-featured web app series by Corey Schafer.

## Projects

### Boilerplates

* [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) ⭐ 4,958 | 🐛 268 | 🌐 Python | 📅 2026-07-10 - Rapid app builder with security, auto CRUD, and charts.
* [cookiecutter-flask](https://github.com/cookiecutter-flask/cookiecutter-flask) ⭐ 4,722 | 🐛 24 | 🌐 Python | 📅 2025-12-02 - Cookiecutter template with Bootstrap, Webpack, and authentication.
* [uwsgi-nginx-flask-docker](https://github.com/tiangolo/uwsgi-nginx-flask-docker) ⭐ 3,005 | 🐛 1 | 🌐 Python | 📅 2026-08-25 - Docker image with uWSGI, Nginx, and Flask.
* [fbone](https://github.com/imwilsonxu/fbone) ⭐ 1,702 | 🐛 24 | 🌐 Python | 📅 2022-05-17 - Classic Flask skeleton with a structured application layout.
* [Flask-Foundation](https://github.com/JackStouffer/Flask-Foundation) ⭐ 1,277 | 🐛 3 | 🌐 Python | 📅 2023-05-01 - Best-practice starter application.

### Open Source Projects

* [Apache Superset](https://github.com/apache/superset) ⭐ 74,498 | 🐛 626 | 🌐 Python | 📅 2026-08-28 - Data exploration and visualization platform.
* [Apache Airflow](https://github.com/apache/airflow) ⭐ 46,623 | 🐛 1,973 | 🌐 Python | 📅 2026-08-27 - Platform to author, schedule, and monitor workflows.
* [Redash](https://github.com/getredash/redash) ⭐ 28,766 | 🐛 802 | 🌐 Python | 📅 2026-08-18 - Query and visualize data from many sources.
* [SimpleLogin](https://github.com/simple-login/app) ⭐ 6,952 | 🐛 256 | 🌐 Python | 📅 2026-08-25 - Email alias service that protects personal inboxes.
* [SecureDrop](https://github.com/freedomofpress/securedrop) ⭐ 3,878 | 🐛 462 | 🌐 Python | 📅 2026-08-28 - Whistleblower submission system for newsrooms.
* [Timesketch](https://github.com/google/timesketch) ⭐ 3,397 | 🐛 221 | 🌐 Python | 📅 2026-08-24 - Collaborative forensic timeline analysis.
* [FlaskBB](https://github.com/flaskbb/flaskbb) ⭐ 2,660 | 🐛 11 | 🌐 Python | 📅 2026-08-22 - Classic forum software built with Flask.
* [Indico](https://github.com/indico/indico) ⭐ 2,100 | 🐛 880 | 🌐 Python | 📅 2026-08-27 - Event management system developed at CERN.
* [SkyLines](https://github.com/skylines-project/skylines) ⭐ 407 | 🐛 107 | 🌐 Python | 📅 2026-08-26 - Live tracking and flight database for gliding.
* [PythonBuddy](https://github.com/ethanchewy/PythonBuddy) ⭐ 281 | 🐛 17 | 🌐 Python | 📅 2026-02-20 - Online Python editor with live syntax checking.

## Hosting

* [Flask Deployment Options](https://flask.palletsprojects.com/en/stable/deploying/) - Official notes on WSGI servers and platforms.
* [Fly.io](https://fly.io/docs/python/frameworks/flask/) - Deploy Flask close to users on Fly Machines.
* [Google Cloud Run](https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-python-service) - Container hosting that works well with Flask.
* [PythonAnywhere](https://help.pythonanywhere.com/pages/Flask/) - Hosted Python environment with first-class Flask support.
* [Render](https://render.com/docs/deploy-flask) - Web services and background workers for Flask.
* [Zappa](https://github.com/zappa/Zappa) ⭐ 3,691 | 🐛 22 | 🌐 Python | 📅 2026-07-15 - Deploy WSGI apps to AWS Lambda and API Gateway.

## Contributing

Suggestions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) first. Historical and unmaintained entries live in [archived.md](archived.md).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
