| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Variable(s)

&nbsp;&nbsp; **&#10148; ISVGAnalyzer**

| Type                        |
|-----------------------------|
| any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Initializer**

```ts
DI.createInterface<ISVGAnalyzer>('ISVGAnalyzer').withDefault(x => x.singleton(class {
  public isStandardSvgAttribute(node: INode, attributeName: string): boolean {
    return false;
  }
}))
```