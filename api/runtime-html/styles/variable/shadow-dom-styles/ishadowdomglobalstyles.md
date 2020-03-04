| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; IShadowDOMGlobalStyles**

| Type                        |
|-----------------------------|
| any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<IShadowDOMStyles>('IShadowDOMGlobalStyles')
  .withDefault(x => x.instance(noopShadowDOMStyles))
```