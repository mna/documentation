---
description: Echo the given string
---

# ECHO

## Syntax

    ECHO message

**Time complexity:** O(1)

Returns `message`.

## Return

[Bulk string reply](https://redis.io/docs/reference/protocol-spec#resp-bulk-strings)

## Examples

```shell
dragonfly> ECHO "Hello World!"
"Hello World!"
```
