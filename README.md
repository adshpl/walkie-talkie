# walkie-talkie-web-client

### Description
In-browser P2P chat on top of WebRTC.\
Developed in 2017.

### Technology stack
* `react` - component system and rendering.
* `immutable` - immutable collections, used as model system for Redux.
* `react-router` - routing.
* `redux` - state system.
* `redux-saga` - side effect manager.
* `browser-bunyan` - logger, based on Bunyan.
* `formsy-react` - forms implementation for React.
* `jest` - testing framework.
* `enzyme` - testing utility to test React components.
* `webpack` - build system.
* `babel` - transpiler to ES6.
* `cssnano` - CSS optimization.
* `eslint` - linter.
* `postcss` - CSS transpiler for CSSNext and syntax sugar.

### How to use this project?
* `yarn run clean:build` - remove build output folder.
* `yarn run prod` - run production build via WebPack.
* `yarn run dev` - run development build via WebPack.
* `yarn run lint` - run linter.
* `yarn run test` - run tests via Jest.

### GIT
Git naming convention is a fork of [Conventional Commits](https://www.conventionalcommits.org/) specification.

#### Example
![example](./Git%20Conventional%20Example.png)