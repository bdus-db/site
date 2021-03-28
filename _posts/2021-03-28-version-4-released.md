---
title:  "Version 4.0.0 released"
author:  "Julian Bogdani"
email:  "julian.bogdani@uniroma1.it"
---


Version 4 has finally been released and the good ol’ version 3 has been deprecated
after 8 years of distinguished service.
While common ysers will notice onlyb minor graphical changes, 
an almost total rewrite of the project is done under the hood.

A huge effort has been spent on keeping things working and making 
the migration of the available applications as smooth as possibile.
This new version opens the door to future rewriting of the GUI, by
clearly separatng the application logic from the data presentation.

The most important new features are:
- the possibility of interchangeably using SQLite, MySQL, MariaDB 
or PostgreSQL as database engines and data storage
- easily [creating a new application](https://docs.bdus.cloud/create_app/) using GUI tools
- easily managing settingd and database schema using GUI features: 
adding, renaming and removing tables, columns, relations has never been so easy
- a totally [new API](https://docs.bdus.cloud/api/) with a secure and flexible query language shaped after SQL,
and named [ShortSQL](https://docs.bdus.cloud/api/shortsql) to easily and securely 
query your data and build new applications.
- a new guide and documentation site availabe at [https://docs.bdus.cloud/](https://docs.bdus.cloud/)
- more that 200 automated unit tests to rapidly and thoroughly test various parts of the lifecycle
of the application, from creation to configuration and data management, for SQLite, MySQL/MariaDB and PostgreSQL.
- Four different hosting solutions:
    - stable version 4
    - legacy version 3
    - a free to use educational version 4, for younger researchers
    - a development and testing version.

In the next weeka all available applcations will be migrated to the new version 3 and hopefully we will 
be able to definitively retire v3.

As usual, stay tuned and help testing and bug detection! [Read the docs](https://docs.bdus.cloud/) and 
[file an issue](https://github.com/bdus-db/BraDypUS/issues) is something is not working as expected!