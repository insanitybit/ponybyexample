# 1 Hello World

```pony
"""
  Pony is a new language with first class support for
  the Actor Model, which makes writing highly efficient, concurrent code easy.

  Below we can see a minimal Pony program - a classic Hello World.
"""
  actor Main
  new create(env: Env) =>
    env.out.print("Hello, world!")
```

If ponyc is installed, compiling is simple:

```bash
ponyc .
```

And out will pop an executable file named 'pony'.

When we run the pony binary ```./pony``` we will se the string ```"Hello, World!"``` printed out.

Congrats! You've just compiled and run your first Pony program.

Note that pony will compile a fully optimized binary by default. Run with ```--debug``` for an unoptimized build.
