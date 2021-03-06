# VueFeedbackReaction

> Helps you to collect feedback and leads using the most spoken language in the world: the emoji.

[![NPMVERSION](https://img.shields.io/npm/v/vue-feedback-reaction.svg)](http://npmjs.com/package/vue-feedback-reaction) [![GITHUBSTARS](https://img.shields.io/github/stars/IvanSotelo/VueFeedbackReaction.svg)](https://github.com/IvanSotelo/VueFeedbackReaction/stargazers) [![MadeWithVueJs.com shield](https://madewithvuejs.com/storage/repo-shields/1774-shield.svg)](https://madewithvuejs.com/p/vuefeedbackreaction/shield-link) [![BUILD](https://travis-ci.org/IvanSotelo/VueFeedbackReaction.svg?branch=master)](https://travis-ci.org/IvanSotelo/VueFeedbackReaction) [![DOWNLOADS](https://img.shields.io/npm/dt/vue-feedback-reaction.svg)](https://npmjs.com/package/vue-feedback-reaction)
[![Build Status](https://github.com/IvanSotelo/VueFeedbackReaction/workflows/Build/badge.svg)](https://github.com/IvanSotelo/VueFeedbackReaction/actions)

This project is inspired by [Feedback Reactions](https://dribbble.com/shots/4793955-Feedback-Reactions) from [Mohammad Amiri](https://dribbble.com/pixelamiri)

## Installation

``` bash
# Install with npm
$ npm i -S vue-feedback-reaction

# or yarn
$ yarn add vue-feedback-reaction
```


## Usage

``` vue
<template>
  <div class="app">
    <vue-feedback-reaction v-model="feedback"/>
  </div>
</template>

<script>
  import VueFeedbackReaction from 'vue-feedback-reaction';
  export default {
    name: 'demo',
    components: {
      VueFeedbackReaction
    }
  };
</script>
```

## License

```
The MIT License (MIT)

Copyright (c) 2019 Ivan Sotelo Vargas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
