# Deepio Boost_boneyard

## How do I install these formulae?
`brew install deepio/boost_boneyard/<formula>`

Or `brew tap deepio/boost_boneyard` and then `brew install <formula>`.

Or install via URL (which will not receive updates):

```
brew install https://raw.githubusercontent.com/deepio/homebrew-boost_boneyard/master/Formula/<formula>.rb
```

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).


## When ready, build bottle and host it somewhere
```
--build-bottle

   bottle [options] formula
       Generate a bottle (binary package) from a formula that was installed with --build-bottle. If the formula specifies a rebuild version, it will be incremented  in
       the generated DSL. Passing --keep-old will attempt to keep it at its original value, while --no-rebuild will remove it.

       --skip-relocation
              Do not check if the bottle can be marked as relocatable.

       --force-core-tap
              Build a bottle even if formula is not in homebrew/core or any installed taps.

       --no-rebuild
              If the formula specifies a rebuild version, remove it from the generated DSL.

       --keep-old
              If the formula specifies a rebuild version, attempt to preserve its value in the generated DSL.

       --json Write bottle information to a JSON file, which can be used as the value for --merge.

       --merge
              Generate an updated bottle block for a formula and optionally merge it into the formula file. Instead of a formula name, requires the path to a JSON file
              generated with brew bottle --json formula.

       --write
              Write changes to the formula file. A new commit will be generated unless --no-commit is passed.

       --no-commit
              When passed with --write, a new commit will not generated after writing changes to the formula file.

       --root-url
              Use the specified URL as the root of the bottle's URL instead of Homebrew's default.
```