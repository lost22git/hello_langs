
# Hello

Comparison of *hello world* **static-linking** binary file sizes in various languages


| OS      | LIBC | PIE      | Build ID |
|---------|------|----------|----------|
| Windows | msvc | none     | none     | 
| Linux   | musl | disabled | none     |


## Build

```sh
just build
```

## Check 

```sh
just ls

just run

just file

just ldd
```

