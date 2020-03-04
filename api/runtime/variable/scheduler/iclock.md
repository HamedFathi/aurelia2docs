| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; IClock**

| Type                        |
|-----------------------------|
| any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<IClock>('IClock').withDefault(x => x.instance(globalClock))
```