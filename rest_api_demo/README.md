rest_api_demo
=============

This repository contains boilerplate code for a RESTful API based on Flask and Flask-RESTPlus.

The code of this demo app is described in an article on blog:
http://michal.karzynski.pl/blog/2016/06/19/building-beautiful-restful-apis-using-flask-swagger-ui-flask-restplus/

├── api                         #
│   ├── blog                    #  Blog-related API directory
│   │   ├── business.py         #
│   │   ├── endpoints           #  API namespaces and REST methods
│   │   │   ├── categories.py   #
│   │   │   └── posts.py        #
│   │   ├── parsers.py          #  Argument parsers
│   │   └── serializers.py      #  Output serializers
│   └── restplus.py             #  API bootstrap file
├── app.py                      #  Application bootstrap file
├── database                    #
│   └── models.py               #  Definition of SQLAlchemy models
├── db.sqlite                   #
└── settings.py                 #  Glob
