| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | Record&lt;string, any&gt; &#124; undefined | ✘ | ✘  | ✔ |

# &#10025; Summary

Efficiently merge parts, performing the minimal amount of work / using the minimal amount of memory.
If either of the two part records is undefined, the other will simply be returned.
If both are undefined, undefined will be returned.
If neither are undefined, a new object will be returned where parts of the second value will be written last (and thus may overwrite duplicate named parts).
This function is idempotent via a WeakMap cache: results are cached and if the same two variables are provided again, the same object will be returned.

&nbsp;&nbsp; **&#9733; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; parentParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Record&lt;string, any&gt; &#124; undefined | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**&#10149; ownParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| - | Record&lt;string, any&gt; &#124; undefined | ✘  | ✘ | ✘ |