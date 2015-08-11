Pass the URL of the Oracle server with `URL` envvar:

```
$ docker run -e URL=<user>/<password>@//xxx.yyy.eu-west-1.rds.amazonaws.com:1521/ORCL -ti sflyr/sqlplus

SQL*Plus: Release 11.2.0.3.0 Production on Tue Aug 11 15:41:07 2015

Copyright (c) 1982, 2011, Oracle.  All rights reserved.


Conectado a:
Oracle Database 11g Release 11.2.0.1.0 - 64bit Production

SQL> _
```
