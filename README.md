# hygen-CRA

This is a hygen package for [create-react-app (CRA)](https://github.com/facebook/create-react-app) that supercharges your workflow.

## Quick Start

```
$ npm i -g hygen-add
$ cd your-CRA && hygen-add CRA
```

Then use `help` to see what the generator can do:

```
$ hygen component help


hygen component new --name NAME [--stateful] [--functional]

Generates a React component, a storybook, and a test.

   NAME           The component name in kebab-case (required).
   --stateful     Generate a stateful component (optional).
   --functional   Generate a functional component (optional).

If no flags given, will generate a PureComponent.


Requires storybook to be installed and initialized:
    $ npm i -g @storybook/cli && getstorybook

Requires react-test-renderer to be installed:
    $ yarn add --dev react-test-renderer
```
