Core differences between type and interface

Both describe the shape of data, and for plain objects they work almost the same. These are the real differences.

Differences between type and interface:

1.Interface only describes object shapes but type can name any type.

2.Two interfaces with the same name merge into one. Two types with the same name cause an error. 3. Interface extends reports an error if the properties conflict. Types does not always do so which can hide bugs. 4. Types supports mapped and conditional type. But Interface doesn't support it.

Choosing Between type and interface in TypeScript:
Choose interface when:
1.You are describing an object or a class contract.
2.You are building a library or public API.
3.You have a hierarchy of related objects
Choose type when:
1.You need a union.
2.You need a tuple or primitive alias.
3.You need advanced type logic.
