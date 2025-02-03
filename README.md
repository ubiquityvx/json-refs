# json-refs
This is a customization of the `json-refs` package with a new function:     
```
resolveRefsExtended(obj: any[] | object, options?: JsonRefsOptions, processChildren?: boolean): Promise<ResolvedRefsResults>;
```

It lets us use `#ref` tags in a json documen similar to how they work with json-schema.

## Documentation

The documentation for this project can be found at <https://github.com/whitlockjc/json-refs/blob/master/docs/README.md>.