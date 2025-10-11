# Your Project

Run `hpack` to generate the `.cabal` file.

Use `watchexec`:
```sh
watchexec -e project,hs,yaml hpack
```

You may need to run `cabal install tasty-discover` as well.
