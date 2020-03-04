| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | any |

# &#10025; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | any        |

# &#10025; Initializer

```ts
ResourceType<T, ICustomElementViewModel & (T extends Constructable<infer P> ? P : {}), PartialCustomElementDefinition>
```