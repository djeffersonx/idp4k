-----------------
# idp4k

###### _Idempotence for kotlin._

-----------------

This is a set projects to easily reach idempotent processes in kotlin.

### idp4k-orchestrator

This project defines the core of the idp4k project provinding the `LockManager` interface and creating the `IdempotenceManager` implementation that has the responsibility to manage the process of idempotence using the `LockManager` to decide treatment to provide to the actual execution.

### idp4k-spring

Provides a Spring auto-configuration.

### idp4k-aop

...

### idp4k-test

...

### lock-management
#### idp4k-lm-postgresql

...

### response-storage
#### idp4k-rs-postgresql
