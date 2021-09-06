# React Modal test issue

If `moduleNameMapper` object has `env` entry in jest config then the content of the modal is not rendered using react-testing-library

Reproduction steps:
1) run `yarn` to install dependencies
2) run `yarn test` - confirm that the test passes
3) uncomment 4th line in `jest.config.js`
4) run `yarn test` - confirm that the test fails, no modal content is present

Related [GH issue](https://github.com/reactjs/react-modal/issues/900)
