![](https://pbs.twimg.com/profile_images/828490798480052225/Sp0fIxul_200x200.jpg)
# RethinkDB

[Official page](https://rethinkdb.com/ "Official page")
<br>
[Docs](https://rethinkdb.com/docs "Docs")

## What is RethinkDB?
- Open-source database for building realtime web applications
- NoSQL database that stores schemaless JSON documents
- Distributed database that is easy to scale
- High availability database with automatic failover and robust fault tolerance

RethinkDB is the first open-source scalable database built for realtime applications. It exposes a new database access model, in which the developer can tell the database to continuously push updated query results to applications without polling for changes. RethinkDB allows developers to build scalable realtime apps in a fraction of the time with less effort.

### Suitable for
- Web + mobile apps
- Multiplayer games
- Realtime marketplaces
- Streaming analytics
- Connected devices

### Supported languages

#### Official drivers
* [**JavaScript**](https://rethinkdb.com/docs/guide/javascript/)
* [**Python**](https://rethinkdb.com/docs/guide/python/)
* [**Ruby**](https://rethinkdb.com/docs/guide/ruby/)
* [**Java**](https://rethinkdb.com/docs/guide/java/)

#### Third-party drivers
* **C#/.NET:** [RethinkDb.Driver](https://github.com/bchavez/RethinkDb.Driver), [rethinkdb-net](https://github.com/mfenniak/rethinkdb-net)
* **C++:** [librethinkdbxx](https://github.com/AtnNn/librethinkdbxx)
* **Clojure:** [clj-rethinkdb](https://github.com/apa512/clj-rethinkdb)
* **Elixir:** [rethinkdb-elixir](https://github.com/rethinkdb/rethinkdb-elixir)
* **Go:** [GoRethink](https://github.com/dancannon/gorethink)
* **Haskell:** [haskell-rethinkdb](https://github.com/atnnn/haskell-rethinkdb)
* **PHP:** [php-rethink-ql](https://github.com/tbolier/php-rethink-ql)
* **Rust:** [reql](https://github.com/rust-rethinkdb/reql)
* **Scala:** [rethink-scala](https://github.com/kclay/rethink-scala)

## Installation with docker

#### Pre-requirements
- docker

#### Deployment
1. Open terminal and clone current repo
2. Go to the folder with .yml file
3. Run `docker-compose up -d`

After that, you can go to the administration console at http://localhost:8080/

[Usage cheat sheet](https://gist.github.com/bradtraversy/6aef077f93c48465891f12958b84a22d "Usage cheat sheet")
