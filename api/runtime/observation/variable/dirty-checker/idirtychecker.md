| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; IDirtyChecker**

| Type                        |
|-----------------------------|
| any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<IDirtyChecker>('IDirtyChecker').withDefault(x => x.singleton(DirtyChecker))
```