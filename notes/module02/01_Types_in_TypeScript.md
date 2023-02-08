# Types in Typescript

- The maine benefit of Typescript: Enables to add static types to the JavaScript code.

## Declaring variables

TypeScript encourages to use `let` and `const` keywords for variable declarations.

## Type inference in TypeScript

- To declare an `explicit` type: use the syntax `varaibleName: typeName`
- To delcare an `implicit` type: declare the variable with initializing ex. `let foo = 10`
- If the variable wasn't assigned to a type or initialized, TypeScript will infer the variables type to `any`.

## Types and subtypes in Typescript

### `Any` Type

- All types in TypeScript are **subtypes** of a sing top type call the `any` type.
- `any`: Type that can represent any JavaScrpt value with **no constraints**.

### Primitive Types

- `boolean`, `number`, `string`, `void`, `null`, `undefined`, user-defined enumeration or `enum` types.
- `void`: Purely to indicate the absence of a value. ex) function with no return value
- `null` and `undefined`: subtypes of all other types. Impossible to explicitly reference.

### Object types and type parameters

- Anything that isn't a `primitive type` is a `object` type.
- `class`, `interface`, `array`, and `literal types`.
- `Class` and `interface` types are introduced through class and interface delcarations.
- `Class` and `interface` types are referenced by the name given to them in their declarations.

