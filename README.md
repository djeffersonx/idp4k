-----------------
# idp4k

###### _Idempotence for kotlin._

-----------------

This is a set projects to easily reach idempotent processes in kotlin.

### idp4k-orchestrator

This project defines the core orchestrator of the idp4k project providing the `LockManager` interface and creating the `IdempotenceOrchestrator` implementation that has the responsibility to manage the idempotent process using the `LockManager`. Calling the right treatment for each process execution instance, based on the configured idempotence key.

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
