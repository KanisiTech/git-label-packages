# git-label-packages

Our repository labels for use with [git-label](https://github.com/jasonbellamy/git-label)

Having consistent labels for PRs and Issues across the Organization makes it
easier to work across multiple repositories.

## Getting Started

- Install with [NPM](https://www.npmjs.org/) - `npm install --save git-label-packages`

## Usage

You can use these packages with both [git-label](https://github.com/jasonbellamy/git-label) and [git-label-cli](https://github.com/jasonbellamy/git-label-cli).

Packages are just simple JSON arrays that contain an object with a name and hexidecimal color property for each label:

```json
[
  { "name": "bug", "color": "#fc2929" },
  { "name": "duplicate", "color": "#cccccc" },
  { "name": "enhancement", "color": "#84b6eb" },
  { "name": "help wanted", "color": "#159818" },
  { "name": "invalid", "color": "#e6e6e6" },
  { "name": "question", "color": "#cc317c" },
  { "name": "wontfix", "color": "#ffffff" }
]
```
