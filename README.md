Welcome to Shaun's monorepo.  The philosophy driving this monorepo's design is to be as frictionless of a component mono repo as possible.  It should be easy to add/test as well how to consume it.

# Table of Contents

1. [Installation](#installation)
2. [Contributing](#contributing)
## Installation
To import and use a component in your project, simply add a "@
## Contributing

To  get a dev server going, run these commands at the root -

`yarn bootstrap`

`yarn storybook`

This will load a storybook development environment that aggregates every `*.story.tsx` file in the `packages` folder.´

### Making Changes
  You MUST commit changes using the following command:
  
  `yarn commit`

  This will walk you through a prompt.  You can eventually do these commits manually in your favorite editor.  They will just have to follow a specific format.  
  TODO: Setup a WIP tag