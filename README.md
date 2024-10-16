## SQLite

SQLite is a database engine written in the C programming language. It is not a standalone app; rather, it is a library that software developers embed in their apps. As such, it belongs to the family of embedded databases. It is the most widely deployed database engine, as it is used by several of the top web browsers, operating systems, mobile phones, and other embedded systems.

#### To use the storage you need to provide only 2 things:

- Session Id - a unique identifier of the session, like user name, email, chat id etc.
- Connection string - a string that specifies the database connection. For SQLite, that string is slqlite:/// followed by the name of the database file. If that file doesn't exist, it will be created.


### File need to install
1. langchain_community
2. langchain-openai - You can use any other opensource mode