<p align="center">
  <a href="https://mpds.f3m.pt/" rel="noopener" target="_blank"><img width="350" src="https://i.imgur.com/OANOfLI.png" alt="MPDS logo"></a></p>
</p>

<h1 align="center">MpDS Back-To-Top</h1>

<div align="center">

[React](https://reactjs.org/) component for faster and simpler web development.
<!--
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mui-org/material-ui/blob/master/LICENSE)
[![npm latest package](https://img.shields.io/npm/v/@material-ui/core/latest.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm next package](https://img.shields.io/npm/v/@material-ui/core/next.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm downloads](https://img.shields.io/npm/dm/@material-ui/core.svg)](https://www.npmjs.com/package/@material-ui/core)
[![CircleCI](https://img.shields.io/circleci/project/github/mui-org/material-ui/next.svg)](https://app.circleci.com/pipelines/github/mui-org/material-ui?branch=next)
[![Coverage Status](https://img.shields.io/codecov/c/github/mui-org/material-ui/next.svg)](https://codecov.io/gh/mui-org/material-ui/branch/next)
[![Follow on Twitter](https://img.shields.io/twitter/follow/MaterialUI.svg?label=follow+Material-UI)](https://twitter.com/MaterialUI)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=mui-org/material-ui)](https://dependabot.com)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/mui-org/material-ui.svg)](https://isitmaintained.com/project/mui-org/material-ui 'Average time to resolve an issue')
[![Crowdin](https://badges.crowdin.net/material-ui-docs/localized.svg)](https://translate.material-ui.com/project/material-ui-docs)
[![Open Collective backers and sponsors](https://img.shields.io/opencollective/all/material-ui)](https://opencollective.com/material-ui) -->

</div>

## Installation

MpDS Back-To-Top is available as an [npm package](npm i mpds-back-to-top).

```sh
// with npm
npm i mpds-back-to-top

```
## Usage

Here is a quick example to get you started, **it's all you need**:

```tsx
import * as React from "react";
import MpdsBackToTop from "mpds-back-to-top"

function App() {
  return <MpdsBackToTop typeOfThePosition="absolute"></MpdsBackToTop>
}

ReactDOM.render(<App />, document.querySelector('#app'));
```

<h4>Props</h4>

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <span>typeOfThePosition</span>
      </td>
      <td>
        <div>
          <span>CSS position gave to the element.</span>
        </div>
        <div>
          <div>
            <span>"static"</span>
            <span>"absolute"</span>
            <span>"fixed"</span>
            <span>"relative"</span>
            <span>"sticky"</span>
            <span>"initial"</span>
            <span>"inherit"</span>
          </div>
        </div>
      </td>
      <td>
        <div>
          <span>static</span>
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <span>classes</span>
      </td>
      <td>
        <div>
          <span>Classes in the button element.</span>
        </div>
        <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>timeOfTransition</span>
      </td>
      <td>
        <div>
          <span>The duration for the transition, in milliseconds.</span>
        </div>
        <div>
          <div>
            <span>number</span>
          </div>
        </div>
      </td>
      <td>
        <div>
          <span>1000</span>
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <span>handleClick</span>
      </td>
      <td>
        <div>
          <span>Callback fired when element is clicked.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
  </tbody>
</table>
<br>
Yes, it's really all you need to get started! Try it in:
[CodeSandbox](https://codesandbox.io/)
<br>

## License

No License. "(...) nobody else can copy, distribute, or modify your work without being at risk of take-downs, shake-downs, or litigation."
