---
id: FieldMetaBase
title: FieldMetaBase
---

<!-- DO NOT EDIT: this page is autogenerated from the type comments -->

# Type Alias: FieldMetaBase\<TParentData, TName, TData, TOnMount, TOnChange, TOnChangeAsync, TOnBlur, TOnBlurAsync, TOnSubmit, TOnSubmitAsync, TFormOnMount, TFormOnChange, TFormOnChangeAsync, TFormOnBlur, TFormOnBlurAsync, TFormOnSubmit, TFormOnSubmitAsync\>

```ts
type FieldMetaBase<TParentData, TName, TData, TOnMount, TOnChange, TOnChangeAsync, TOnBlur, TOnBlurAsync, TOnSubmit, TOnSubmitAsync, TFormOnMount, TFormOnChange, TFormOnChangeAsync, TFormOnBlur, TFormOnBlurAsync, TFormOnSubmit, TFormOnSubmitAsync> = object;
```

Defined in: [packages/form-core/src/FieldApi.ts:521](https://github.com/TanStack/form/blob/main/packages/form-core/src/FieldApi.ts#L521)

## Type Parameters

• **TParentData**

• **TName** *extends* [`DeepKeys`](deepkeys.md)\<`TParentData`\>

• **TData** *extends* [`DeepValue`](deepvalue.md)\<`TParentData`, `TName`\>

• **TOnMount** *extends* `undefined` \| `FieldValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnChange** *extends* `undefined` \| `FieldValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnChangeAsync** *extends* `undefined` \| `FieldAsyncValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnBlur** *extends* `undefined` \| `FieldValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnBlurAsync** *extends* `undefined` \| `FieldAsyncValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnSubmit** *extends* `undefined` \| `FieldValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TOnSubmitAsync** *extends* `undefined` \| `FieldAsyncValidateOrFn`\<`TParentData`, `TName`, `TData`\>

• **TFormOnMount** *extends* `undefined` \| `FormValidateOrFn`\<`TParentData`\>

• **TFormOnChange** *extends* `undefined` \| `FormValidateOrFn`\<`TParentData`\>

• **TFormOnChangeAsync** *extends* `undefined` \| `FormAsyncValidateOrFn`\<`TParentData`\>

• **TFormOnBlur** *extends* `undefined` \| `FormValidateOrFn`\<`TParentData`\>

• **TFormOnBlurAsync** *extends* `undefined` \| `FormAsyncValidateOrFn`\<`TParentData`\>

• **TFormOnSubmit** *extends* `undefined` \| `FormValidateOrFn`\<`TParentData`\>

• **TFormOnSubmitAsync** *extends* `undefined` \| `FormAsyncValidateOrFn`\<`TParentData`\>

## Type declaration

### errorMap

```ts
errorMap: ValidationErrorMap<UnwrapFieldValidateOrFn<TName, TOnMount, TFormOnMount>, UnwrapFieldValidateOrFn<TName, TOnChange, TFormOnChange>, UnwrapFieldAsyncValidateOrFn<TName, TOnChangeAsync, TFormOnChangeAsync>, UnwrapFieldValidateOrFn<TName, TOnBlur, TFormOnBlur>, UnwrapFieldAsyncValidateOrFn<TName, TOnBlurAsync, TFormOnBlurAsync>, UnwrapFieldValidateOrFn<TName, TOnSubmit, TFormOnSubmit>, UnwrapFieldAsyncValidateOrFn<TName, TOnSubmitAsync, TFormOnSubmitAsync>>;
```

A map of errors related to the field value.

### isBlurred

```ts
isBlurred: boolean;
```

A flag indicating whether the field has been blurred.

### isDirty

```ts
isDirty: boolean;
```

A flag that is `true` if the field's value has been modified by the user. Opposite of `isPristine`.

### isTouched

```ts
isTouched: boolean;
```

A flag indicating whether the field has been touched.

### isValidating

```ts
isValidating: boolean;
```

A flag indicating whether the field is currently being validated.
