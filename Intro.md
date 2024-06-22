# Typescript

- Alternative to Javascript
- Typescript is a superset of Javascript. That means any valid Javascript code is also valid Typescript code.
- It allows us to use strict types.
- Supports modern features of Javascript such as `classes, arrow functions, and modules.`
- Extra features include `generics, interfaces, tuples` etc.
- Browsers do not understand Typescript. It needs to be compiled to Javascript at runtime.

![Typescript](https://i.imgur.com/wAr29gQ.png)

# Compiling Typescript

- As Tyescript is not understood by browsers, it needs to be compiled to Javascript.

- To compile a Typescript file, we can use the `tsc` command followed by the name of the file.

```bash
tsc file.ts
```

- This will create a new file with the same name but with a `.js` extension.

- This approach will require us to recomplie the file every time we make a change.

- To automatically compile the file every time we make a change, we can use the `--watch` or `-w` flag.

```bash
tsc file.ts -w
```

 

