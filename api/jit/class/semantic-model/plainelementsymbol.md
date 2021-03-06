# &#10025; Summary

A normal html element that may or may not have attribute behaviors and/or child node behaviors.
It is possible for a PlainElementSymbol to not yield any instructions during compilation.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

# &#10025; Type Parameter(s)

| Type  | Constraint |
| ----- | ---------- |
| TText | any        |

| Type     | Constraint |
| -------- | ---------- |
| TElement | any        |

| Type    | Constraint |
| ------- | ---------- |
| TMarker | any        |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; dom**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| any | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; physicalNode**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| TElement | ✘  | ✘ | ✔ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; flags**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | [SymbolFlags](/jit/enum/semantic-model/symbolflags.md) |

&nbsp;&nbsp; **&#10148; isTarget**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | boolean |

&nbsp;&nbsp; **&#10148; templateController**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | [TemplateControllerSymbol](/jit/class/semantic-model/templatecontrollersymbol.md)&lt;TText, TElement, TMarker&gt; &#124; null |

&nbsp;&nbsp; **&#10148; hasSlots**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | boolean |

&nbsp;&nbsp; **&#10148; &#95;customAttributes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✘ | [CustomAttributeSymbol](/jit/class/semantic-model/customattributesymbol.md)[] &#124; null |

&nbsp;&nbsp; **&#10148; &#95;plainAttributes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✘ | [PlainAttributeSymbol](/jit/class/semantic-model/plainattributesymbol.md)[] &#124; null |

&nbsp;&nbsp; **&#10148; &#95;childNodes**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| private | ✘ | NodeSymbol&lt;TText, TElement, TMarker&gt;[] &#124; null |

# &#10025; Get Accessor(s)

&nbsp;&nbsp; **&#10148; customAttributes**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [CustomAttributeSymbol](/jit/class/semantic-model/customattributesymbol.md)[] |

&nbsp;&nbsp; **&#10148; plainAttributes**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | [PlainAttributeSymbol](/jit/class/semantic-model/plainattributesymbol.md)[] |

&nbsp;&nbsp; **&#10148; childNodes**

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | NodeSymbol&lt;TText, TElement, TMarker&gt;[] |