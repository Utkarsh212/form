---
id: ObjectDeepKeyAndValue
title: ObjectDeepKeyAndValue
---

<!-- DO NOT EDIT: this page is autogenerated from the type comments -->

# Interface: ObjectDeepKeyAndValue\<TParent, T, TKey\>

Defined in: [packages/form-core/src/util-types.ts:94](https://github.com/TanStack/form/blob/main/packages/form-core/src/util-types.ts#L94)

## Extends

- [`AnyDeepKeyAndValue`](anydeepkeyandvalue.md)

## Type Parameters

• **TParent** *extends* [`AnyDeepKeyAndValue`](anydeepkeyandvalue.md)

• **T**

• **TKey** *extends* [`AllObjectKeys`](../type-aliases/allobjectkeys.md)\<`T`\>

## Properties

### key

```ts
key: ObjectAccessor<TParent, TKey>;
```

Defined in: [packages/form-core/src/util-types.ts:99](https://github.com/TanStack/form/blob/main/packages/form-core/src/util-types.ts#L99)

#### Overrides

[`AnyDeepKeyAndValue`](anydeepkeyandvalue.md).[`key`](AnyDeepKeyAndValue.md#key)

***

### value

```ts
value: ObjectValue<TParent, T, TKey>;
```

Defined in: [packages/form-core/src/util-types.ts:100](https://github.com/TanStack/form/blob/main/packages/form-core/src/util-types.ts#L100)

#### Overrides

[`AnyDeepKeyAndValue`](anydeepkeyandvalue.md).[`value`](AnyDeepKeyAndValue.md#value)
