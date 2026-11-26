# Hello World!

This is a collection of various hello world programms in different languages, used for teaching.
PRs welcome!

## C

- compile:

```
gcc HelloWorld.c -o HelloWorld
```

- run:

```
./HelloWorld
```

## Go

- run:

```
go run HelloWorld.go
```

## HTML

- view:

```
firefox HelloWorld.html
```

## Java

- compile:

```
javac HelloWorld.java
```

- run:

```
java HelloWorld
```

## JavaScript

- run:

```
node HelloWorld.js
```

## Kotlin

- compile:

```
kotlinc HelloWorld.kt
```

- run:

```
java HelloWorldKt
```

## Python

- run:

```
python HelloWorld.py
```

## Rust

- compile:

```
rustc HelloWorld.rs
```

- run:

```
./HelloWorld
```

## SQL

- start a Database:

```
docker run -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=password -e POSTGRES_DB=myDb -p 5432:5432 -d postgres:latest
```

- connect to the Database:

```
psql -d myDb -U postgres
```

- init the table:

```
CREATE TABLE helloworld (phrase TEXT);
```

- add values:

```
INSERT INTO helloworld (phrase) VALUES ('Hello, World from SQL!');
```

- run:

```
psql -d myDb -U postgres -f HelloWorld.sql
```
