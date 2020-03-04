| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IPropertyBindingInstruction](/runtime/interface/definitions/ipropertybindinginstruction.md) |

# &#10025; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; from**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string &#124; IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;any&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#10149; to**

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

# &#10025; Property(ies)

&nbsp;&nbsp; **&#10148; type**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | TargetedInstructionType.propertyBinding |

&nbsp;&nbsp; **&#10148; mode**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | BindingMode.fromView |

&nbsp;&nbsp; **&#10148; oneTime**

| Modifier(s)                               | Optional                           | Type                         |
|-------------------------------------------|:----------------------------------:|------------------------------|
| public | ✘ | false |