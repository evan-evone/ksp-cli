# ksp-cli

A simple script to create aliases for important Kerbal Space Program functions.
By default, it creates an alias `KSP` from the executable within `/Applications/KSP.app`.
You can change this by creating and editing a `options.json` file in
`~/.config/ksp-cli/`:

- For each alias you want created, enter a key `<aliasName>-path`
    - This must have a value that is an executable file
    - This *can* be `ksp-path` to write a new path to the executable
- For each alias with default options, enter a key `<aliasName>-options`
    - This must have a value that is a valid string of flags

