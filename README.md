# py3-database
A Python3 Database Library By Guolei
# Installation
```shell
pip install py3-database
```
# Example
## mysql
### pymysql
```python
from py3_database.pymysql import Database as PymysqlDb

pymysql_db = PymysqlDb(connect_args=(), connect_kwargs={})
pymysql_db.open()
pymysql_db.execute()
pymysql_db.executemany()
pymysql_db.transaction()
pymysql_db.fetchone()
pymysql_db.fetchall()
pymysql_db.rowcount()
pymysql_db.lastrowid()
pymysql_db.close()
```
## sqlite
### sqlite3
```python
from py3_database.sqlite3 import Database as Sqlite3Db

sqlite3_db = Sqlite3Db(connect_args=(), connect_kwargs={})
sqlite3_db.open()
sqlite3_db.execute()
sqlite3_db.executemany()
sqlite3_db.transaction()
sqlite3_db.fetchone()
sqlite3_db.fetchall()
sqlite3_db.rowcount()
sqlite3_db.lastrowid()
sqlite3_db.close()
```
