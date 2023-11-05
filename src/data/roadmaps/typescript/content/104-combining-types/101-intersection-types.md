# Intersection Types

An intersection type creates a new type by combining multiple existing types. The new type has all features of the existing types.

To combine types, you use the `&` operator as follows:

```typescript
type typeAB = typeA & typeB;
```

The `typeAB` will have all properties from both typeA and typeB.

Note that the union type uses the `|` operator that defines a variable which can hold a value of either `typeA` or `typeB`

Learn more from the following links:

- [Intersection Types in TypeScript](https://www.typescripttutorial.net/typescript-tutorial/typescript-intersection-types/)
