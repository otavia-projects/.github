Hi! Welcome to otavia projects! This is the source code of otavia ecosystem!

## Introduction

[Otavia](https://otavia-projects.github.io/otavia/home.html) is an IO and Actor programming model power by Scala 3, it
provides a toolkit to make writing high-performance concurrent programs more easily.

## Ecosystem status

| artifactName            | status | scope         | repository       | what's this                                                                                                                                                                       |
|-------------------------|--------|---------------|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| otavia-buffer           | WIP    | buffer        | otavia           | A zero-deps buffer implementation for replace `java.nio.ByteBuffer` forked from Netty.                                                                                            |
| otavia-serde            | WIP    | serde         | otavia           | A generic serialization and deserialization framework based on `buffer`.                                                                                                          |
| otavia-runtime          | WIP    | runtime       | otavia           | Core Actor model, IO model(channel), slf4a, reactor model, IOC, message model, and thread model.                                                                                  |
| otavia-codec            | WIP    | codec         | otavia           | Some generic ChannelHandler.                                                                                                                                                      |
| otavia-handler          | WIP    | codec         | otavia           | Some special ChannelHandler, eg, SSL, io traffic control, timeout.                                                                                                                |
| otavia-async            | PLAN   | async         | otavia-async     | A implementation of `async/await` transformation for Actor message sending/waiting based on CPS(Continuation Passing Style) transformation powered by metaprogramming of Scala 3. |
| otavia-sql              | WIP    | sql           | otavia           | Actor database connect specification for RDBMS.                                                                                                                                   |
| otavia-sql-macro        | WIP    | sql           | otavia-deriving  | Derivation for class use in `otavia-sql`.                                                                                                                                         |
| otavia-serde-json       | WIP    | json          | otavia           | JSON serialization and deserialization.                                                                                                                                           |
| otavia-json-macro       | PLAN   | json          | otavia-deriving  | Macro for `otavia-serde-json`.                                                                                                                                                    |
| otavia-codec-http       | WIP    | http          | otavia           | HTTP ChannelHandlers and Actors.                                                                                                                                                  |
| otavia-http-macro       | PLAN   | http          | otavia-deriving  | Macro for `otavia-codec-http`.                                                                                                                                                    |
| otavia-serde-proto      | PLAN   | protocol      | otavia           | Protocol buffer serialization and deserialization.                                                                                                                                |
| otavia-proto-macro      | PLAN   | protocol      | otavia-deriving  | Macro for `otavia-serde-proto`.                                                                                                                                                   |
| otavia-codec-haproxy    | PLAN   | codec         | otavia           | Haproxy ChannelHandlers and Actors.                                                                                                                                               |
| otavia-codec-memcache   | PLAN   | codec         | otavia           | Memcache ChannelHandlers and Actors.                                                                                                                                              |
| otavia-codec-mqtt       | PLAN   | codec         | otavia           | MQTT ChannelHandlers and Actors.                                                                                                                                                  |
| otavia-codec-redis      | WIP    | codec         | otavia           | Redis ChannelHandlers and Actors.                                                                                                                                                 |
| otavia-codec-smtp       | PLAN   | codec         | otavia           | SMTP ChannelHandlers and Actors.                                                                                                                                                  |
| otavia-codec-socks      | PLAN   | codec         | otavia           | SOCKS4/5 ChannelHandlers and Actors.                                                                                                                                              |
| otavia-codec-kafka      | PLAN   | codec         | otavia           | KAFKA ChannelHandlers and Actors.                                                                                                                                                 |
| otavia-codec-dns        | PLAN   | codec         | otavia           | DNS ChannelHandlers and Actors.                                                                                                                                                   |
| otavia-mysql-driver     | WIP    | sql/codec     | otavia           | mysql driver for otavia.                                                                                                                                                          |
| otavia-postgres-driver  | WIP    | sql/codec     | otavia           | postgres driver for otavia.                                                                                                                                                       |
| otavia-log4a            | WIP    | logger        | otavia           | A simple slf4a logger implementation.                                                                                                                                             |
| sponge                  | PLAN   | web framework | sponge           | A simple web framework based on otavia ecosystem.                                                                                                                                 |
| otavia-native-transport | PLAN   | io transport  | native-transport | A native io transport via JNI.                                                                                                                                                    |

