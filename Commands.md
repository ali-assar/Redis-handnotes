## Redis Commands

`Commands.md`

### SET

The `SET` command is used to set a value to a key.

```bash
SET key value
```

### GET

The `GET` command is used to get the value of a key.

```bash
GET key
```

### DEL

The `DEL` command is used to delete a key.

```bash
DEL key
```

### INCR

The `INCR` command is used to increment the value of a key by 1.

```bash
INCR key
```

### DECR

The `DECR` command is used to decrement the value of a key by 1.

```bash
DECR key
```

### RPUSH

The `RPUSH` command is used to insert a new value at the end of a list.

```bash
RPUSH list value
```

### LPUSH

The `LPUSH` command is used to insert a new value at the start of a list.

```bash
LPUSH list value
```

### LPOP

The `LPOP` command is used to remove and get the first element in a list.

```bash
LPOP list
```

### RPOP

The `RPOP` command is used to remove and get the last element in a list.

```bash
RPOP list
```

### SADD

The `SADD` command is used to add a member to a set.

```bash
SADD set member
```

### SREM

The `SREM` command is used to remove a member from a set.

```bash
SREM set member
```

### SISMEMBER

The `SISMEMBER` command is used to check if a member is a part of a set.

```bash
SISMEMBER set member
```


## Advanced Redis Commands

`Advanced_Commands.md`

### SETEX

The `SETEX` command is used to set the value of a key with an expiration time (in seconds).

```bash
SETEX key seconds value
```

### PSETEX

The `PSETEX` command works exactly like `SETEX`, but the time to live of the key is specified in milliseconds instead of seconds.

```bash
PSETEX key milliseconds value
```

### MSET

The `MSET` command is used to set multiple keys to multiple values.

```bash
MSET key1 value1 key2 value2
```

### MGET

The `MGET` command is used to get the values of all the given keys.

```bash
MGET key1 key2
```

### EXPIRE

The `EXPIRE` command is used to set an expiration time to an existing key.

```bash
EXPIRE key seconds
```

### TTL

The `TTL` command is used to get the remaining time to live of a key that has an `EXPIRE` set.

```bash
TTL key
```

### FLUSHDB

The `FLUSHDB` command is used to delete all the keys of the currently selected database.

```bash
FLUSHDB
```

### FLUSHALL

The `FLUSHALL` command is used to delete all the keys of all the existing databases, not just the currently selected one.

```bash
FLUSHALL
```
