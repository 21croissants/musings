## Postgres crashed

When tmux crashes, it may not close postgres in a clean way.

```
Could not connect to server: No such file or directory
    Is the server running locally and accepting
    connections on Unix domain socket "/var/pgsql_socket/.s.PGSQL.5432"
```

Just remove the /usr/local/var/postgres/postmaster.pid and restart postgres with launctl and you should be good!
