| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; ISyntaxInterpreter**

| Type                        |
|-----------------------------|
| any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<ISyntaxInterpreter>('ISyntaxInterpreter').withDefault(x => x.singleton(SyntaxInterpreter))
```