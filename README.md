# redmine-cjk
Example of redmine+mariadb for CJK languages on docker-compose.

- modify mysqld character set to utf8mb4.
- add `ENGINE=InnoDB ROW_FORMAT=DYNAMIC` to CREATE TABLE.

# How to use

1. clone this repos.
2. `cd` to cloned dir.
3. run `docker-compose up --build db` to DB initialization.
4. hit `Ctrl-C` after `[Note] mysqld: ready for connections.` shown.
5. run `docker-compose up -d --build`.

# LICENSE

The MIT License.
