# json-refs
This is a customization of the `json-refs` package with a new function:     
```
resolveRefsExtended(obj: any[] | object, options?: JsonRefsOptions, processChildren?: boolean): Promise<ResolvedRefsResults>;
```

It lets us use `#ref` tags in a json document similar to how they work with json-schema.

I also made some modifications that it can run either in the browser or in node. The node-only version has its own branch.

## Documentation

The documentation for this project can be found at <https://github.com/whitlockjc/json-refs/blob/master/docs/README.md>.
