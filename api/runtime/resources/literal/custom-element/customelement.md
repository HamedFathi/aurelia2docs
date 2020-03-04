| Modifier(s)                            |
|----------------------------------------|
| export |

# &#9733; Literal(s)

&nbsp;&nbsp; **&#10148; CustomElement**

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| any | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Member(s)**

| Object                        |
|:-----------------------------:|
| ✔ |

**&#9733; Assignment(s)**

**&#10148; name**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: any; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends any ? any : never; for&lt;T extends [INode](/runtime/interface/dom/inode.md) = INode, C extends [ICustomElementViewModel](/runtime/interface/lifecycle/icustomelementviewmodel.md)&lt;T&gt; = ICustomElementViewModel&lt;T&gt;&gt;(node: T, nameOrSearchParents?: string &#124; boolean &#124; undefined, searchParents?: boolean &#124; undefined): [ICustomElementController](/runtime/interface/lifecycle/icustomelementcontroller.md)&lt;T, C&gt;; define&lt;T extends any&gt;(nameOrDef: any, Type?: T &#124; null &#124; undefined): any; getDefinition&lt;T extends any&gt;(Type: T): [CustomElementDefinition](/runtime/resources/class/custom-element/customelementdefinition.md)&lt;T&gt;; annotate&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K, value: any): void; getAnnotation&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K): any; generateName: () =&gt; string; createInjectable&lt;K extends any = any&gt;(): InjectableToken&lt;K&gt;; generateType: &lt;P extends {} = {}&gt;(name: string, proto?: P) =&gt; any; } | ✘  | ✘ |

**&#9733; Value**

Protocol.resource.keyFor('custom-element')

**&#10148; generateName**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: any; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends any ? any : never; for&lt;T extends [INode](/runtime/interface/dom/inode.md) = INode, C extends [ICustomElementViewModel](/runtime/interface/lifecycle/icustomelementviewmodel.md)&lt;T&gt; = ICustomElementViewModel&lt;T&gt;&gt;(node: T, nameOrSearchParents?: string &#124; boolean &#124; undefined, searchParents?: boolean &#124; undefined): [ICustomElementController](/runtime/interface/lifecycle/icustomelementcontroller.md)&lt;T, C&gt;; define&lt;T extends any&gt;(nameOrDef: any, Type?: T &#124; null &#124; undefined): any; getDefinition&lt;T extends any&gt;(Type: T): [CustomElementDefinition](/runtime/resources/class/custom-element/customelementdefinition.md)&lt;T&gt;; annotate&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K, value: any): void; getAnnotation&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K): any; generateName: () =&gt; string; createInjectable&lt;K extends any = any&gt;(): InjectableToken&lt;K&gt;; generateType: &lt;P extends {} = {}&gt;(name: string, proto?: P) =&gt; any; } | ✘  | ✘ |

**&#9733; Value**

(function () {
let id = 0;
return function () {
return `unnamed-${++id}`;
};
})()

**&#10148; generateType**

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: any; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends any ? any : never; for&lt;T extends [INode](/runtime/interface/dom/inode.md) = INode, C extends [ICustomElementViewModel](/runtime/interface/lifecycle/icustomelementviewmodel.md)&lt;T&gt; = ICustomElementViewModel&lt;T&gt;&gt;(node: T, nameOrSearchParents?: string &#124; boolean &#124; undefined, searchParents?: boolean &#124; undefined): [ICustomElementController](/runtime/interface/lifecycle/icustomelementcontroller.md)&lt;T, C&gt;; define&lt;T extends any&gt;(nameOrDef: any, Type?: T &#124; null &#124; undefined): any; getDefinition&lt;T extends any&gt;(Type: T): [CustomElementDefinition](/runtime/resources/class/custom-element/customelementdefinition.md)&lt;T&gt;; annotate&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K, value: any): void; getAnnotation&lt;K extends string &#124; number &#124; symbol&gt;(Type: any, prop: K): any; generateName: () =&gt; string; createInjectable&lt;K extends any = any&gt;(): InjectableToken&lt;K&gt;; generateType: &lt;P extends {} = {}&gt;(name: string, proto?: P) =&gt; any; } | ✘  | ✘ |

**&#9733; Value**

(function () {
const nameDescriptor: PropertyDescriptor = {
value: '',
writable: false,
enumerable: false,
configurable: true,
};
// eslint-disable-next-line @typescript-eslint/no-explicit-any
const defaultProto = {} as any;
return function <P extends {} = {}> (
name: string,
proto: P = defaultProto,
): CustomElementType<Constructable<P>> {
// Anonymous class ensures that minification cannot cause unintended side-effects, and keeps the class
// looking similarly from the outside (when inspected via debugger, etc).
const Type = class {} as CustomElementType<Constructable<P>>;
// Define the name property so that Type.name can be used by end users / plugin authors if they really need to,
// even when minified.
nameDescriptor.value = name;
Reflect.defineProperty(Type, 'name', nameDescriptor);
// Assign anything from the prototype that was passed in
if (proto !== defaultProto) {
Object.assign(Type.prototype, proto);
}
return Type;
};
})()

**&#9733; Method(s)**

&nbsp;&nbsp; **&#10148; keyFrom**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | string |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; isType**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | boolean |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; for**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [ICustomElementController](/runtime/interface/lifecycle/icustomelementcontroller.md)&lt;T, C&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                               |
| ---- | ---------------------------------------- |
| T    | [INode](/runtime/interface/dom/inode.md) |
| Type | Constraint                                                                                  |
| ---- | ------------------------------------------------------------------------------------------- |
| C    | [ICustomElementViewModel](/runtime/interface/lifecycle/icustomelementviewmodel.md)&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; define**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| T    | any        |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getDefinition**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [CustomElementDefinition](/runtime/resources/class/custom-element/customelementdefinition.md)&lt;T&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| T    | any        |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; annotate**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                         |
| ---- | ---------------------------------- |
| K    | string &#124; number &#124; symbol |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; getAnnotation**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | any |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint                         |
| ---- | ---------------------------------- |
| K    | string &#124; number &#124; symbol |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; -**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | - | ✘  | ✘ | ✘ | - |

&nbsp;&nbsp; **&#10148; createInjectable**

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | InjectableToken&lt;K&gt; |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Type Parameter(s)**

| Type | Constraint |
| ---- | ---------- |
| K    | any        |