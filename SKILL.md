# micronaut.test.core Skill

Use this skill to work with Norm module `micronaut.test.core` version 3. Use only declarations listed below.

## `micronaut.test.core`

Source: `MockBean.norm`

### `MockBean`

```norm
annotation MockBean implements TypeTarget, FieldTarget, FunctionTarget, RuntimeRetention
```

#### `bean`

```norm
Class<?> bean
```

Type: `Class<?>`

#### `named`

```norm
String named
```

Type: `String`

#### `value`

```norm
Class<?> value
```

Type: `Class<?>`

#### `MockBean`

```norm
MockBean(Class<?>? bean, String? named, Class<?>? value)
```

Parameters:

- `bean`: `Class<?>?`
- `named`: `String?`
- `value`: `Class<?>?`

## `micronaut.test.core`

Source: `TransactionMode.norm`

### `TransactionMode`

```norm
enum TransactionMode
```

#### `SEPARATE_TRANSACTIONS`

```norm
SEPARATE_TRANSACTIONS
```

#### `SINGLE_TRANSACTION`

```norm
SINGLE_TRANSACTION
```

