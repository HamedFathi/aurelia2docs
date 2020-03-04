| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | any |

# &#10025; Initializer

```ts
PartialResourceDefinition<{
  readonly cache?: '*' | number;
  readonly template?: unknown;
  readonly instructions?: readonly (readonly ITargetedInstruction[])[];
  readonly dependencies?: readonly Key[];
  readonly injectable?: InjectableToken | null;
  readonly needsCompile?: boolean;
  readonly surrogates?: readonly ITargetedInstruction[];
  readonly bindables?: Record<string, PartialBindableDefinition> | readonly string[];
    readonly childrenObservers?: Record<string, PartialChildrenDefinition>;
      readonly containerless?: boolean;
      readonly isStrictBinding?: boolean;
      readonly shadowOptions?: { mode: 'open' | 'closed' } | null;
      readonly hasSlots?: boolean;
      readonly strategy?: BindingStrategy;
      readonly hooks?: Readonly<HooksDefinition>;
        readonly scopeParts?: readonly string[];
        }>
```