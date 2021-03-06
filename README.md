# git-label-packages

Our repository labels for use with NEW TOOL

Having consistent labels for PRs and Issues across the Organization makes it
easier to work across multiple repositories.

## Usage

Eg
```
# Show help
./apply-github-labels -h

# Apply the 'estimates' labels pack to the KanisiTech/git-label-packages repo
./apply-github-labels -t 123456 -r KanisiTech/git-label-packages -p ./packs/estimates.json
```

Packages are just simple JSON arrays that contain an object with a name, a
description, and a hexidecimal color property for each label:

```json
[
  { "name": "bug", "description": "example text", "color": "fc2929" },
]
```

Note that the hexadecimal colour property must _not_ contain the # character.
