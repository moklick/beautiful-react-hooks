[![Build Status](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks.svg?branch=master)](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![npm](https://img.shields.io/npm/v/beautiful-react-hooks)
![GitHub stars](https://img.shields.io/github/stars/beautifulinteractions/beautiful-react-hooks?style=social)


<div align="center">
  <p align="center">
    <img src="./logo.png" alt="Beautiful React Hooks" width="750px" />
  </p>
</div>
<br />
<div>
  <p align="center">
    A collection of beautiful (and hopefully useful) React hooks to speed-up your 
    components and hooks development
  </p>
</div>

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Live playground here 🌟
    </a>
  </p>
</div>

![Usage example](./usage_example.png)


## 💡 Why? 

React custom hooks allow to abstract components' business logic into single reusable functions.<br />
So far, we've found that most of the hooks we've created and therefore shared between our internal projects have quite often a 
similar gist that involves callback references, events and components' lifecycle. <br />
For this reason we've tried to sum up that gist into `beautiful-react-hooks`: a collection of (*hopefully*) useful 
React hooks to possibly help other companies and professionals to speed up their development process.<br /><br />
Furthermore, we created a concise yet concrete API having in mind the code readability, focusing 
to keep the learning curve as lower as possible so that the it can be used and shared in bigger teams.


**-- Please before using any hook, read its documentation! --**

## ☕️ Features

* Concise API
* Small and lightweight
* Easy to learn
* Functional approach
* Fully written in JS (although TS types are supported)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Live playground here 🌟
    </a>
  </p>
</div>

## 🕺 Install

by using `npm`:
```bash
$ npm install beautiful-react-hooks
```

by using `yarn`:

```bash
$ yarn add beautiful-react-hooks
```

## 🎨 Hooks

* [useGlobalEvent](docs/useGlobalEvent.md)
* [usePreviousValue](docs/usePreviousValue.md)
* [useValueHistory](docs/useValueHistory.md)
* [useValidatedState](docs/useValidatedState.md)
* [useMediaQuery](docs/useMediaQuery.md)
* [useOnlineState](docs/useOnlineState.md)
* [useViewportSpy](docs/useViewportSpy.md)
* [useGeolocation](docs/useGeolocation.md), [useGeolocationState](docs/useGeolocationState.md) and [useGeolocationEvents](docs/useGeolocationEvents.md)
* [useDrag](docs/useDrag.md), [useDragEvents](docs/useDragEvents.md)
* [useMouse](docs/useMouse.md), [useMouseState](docs/useMouseState.md) and [useMouseEvents](docs/useMouseEvents.md)
* [useLifecycle](docs/useLifecycle.md), [useDidMount](docs/useDidMount.md) and [useWillUnmount](docs/useWillUnmount.md)
* [useWindowResize](docs/useWindowResize.md)
* [useWindowScroll](docs/useWindowScroll.md)
* [useRequestAnimationFrame](docs/useRequestAnimationFrame.md)
* [useTimeout](docs/useTimeout.md)
* [useConditionalTimeout](docs/useConditionalTimeout.md)
* [useInterval](docs/useInterval.md)
* [useDebouncedFn](docs/useDebouncedFn.md)
* [useThrottledFn](docs/useThrottledFn.md)
* [useLocalStorage](docs/useLocalStorage.md)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Live playground here 🌟
    </a>
  </p>
</div>

## Contributing

Contributions are very welcome and wanted. 

To submit your custom hook, please make sure your read our [CONTRIBUTING](./CONTRIBUTING.md) guidelines.

**Before submitting** a new merge request, please make sure:

1. You have updated the package.json version and reported your changes into the [CHANGELOG](./CHANGELOG.md) file
3. make sure you run `npm test` and `npm build` before submitting your merge request.
4. make sure you've added the documentation of your custom hook (*you can possibly use the [HOOK_DOCUMENTATION_TEMPLATE](./HOOK_DOCUMENTATION_TEMPLATE.md) to document your custom hook*).
5. make sure you've updated the `index.d.ts` file with your hook types.

### Made with

* [React](https://reactjs.org/)
* [Mocha](https://mochajs.org/)
* [Chai](https://www.chaijs.com/)
* [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro)
* [@testing-library/react-hooks](https://react-hooks-testing-library.com/) 


### Credits

This library is provided and sponsored by: 

<div>
  <p>
    <a href="https://beautifulinteractions.com/">
      <img src="https://beautifulinteractions.com/img/logo-colorful.svg" alt="Beautiful interactions" width="140px" />
    </a>
  </p>
</div>

As part of our commitment to support and contribute to the open source community.

---

Icon made by [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](https://www.flaticon.com/free-icon/hook_1081812)
