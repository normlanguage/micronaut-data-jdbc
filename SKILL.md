# micronaut.data.jdbc Skill

Use this skill to work with Norm module `micronaut.data.jdbc` version 3. Use only declarations listed below.

## `micronaut.data.jdbc`

Source: `Dialect.norm`

### `Dialect`

```norm
enum Dialect
```

#### `ANSI`

```norm
ANSI
```

#### `H2`

```norm
H2
```

#### `MYSQL`

```norm
MYSQL
```

#### `ORACLE`

```norm
ORACLE
```

#### `POSTGRES`

```norm
POSTGRES
```

#### `SQLITE`

```norm
SQLITE
```

#### `SQL_SERVER`

```norm
SQL_SERVER
```

## `micronaut.data.jdbc`

Source: `JdbcRepository.norm`

### `JdbcRepository`

```norm
annotation JdbcRepository implements TypeTarget, RuntimeRetention
```

#### `dataSource`

```norm
String dataSource
```

Type: `String`

#### `dialect`

```norm
Dialect dialect
```

Type: `Dialect`

#### `JdbcRepository`

```norm
JdbcRepository(String? dataSource, Dialect dialect)
```

Parameters:

- `dataSource`: `String?`
- `dialect`: `Dialect`

