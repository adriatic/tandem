---
sidebar-position: 1
---

# testing - introduction

The concept of JavaScript testing is first explained in [RedwoodJS testing](https://redwoodjs.com/docs/testing) document, by using small snippets of JavaScript code and "run" them in [JSFiddle playground](https://jsfiddle.net/).

This document is focused on **_application_** (as different from code snippets) testing, demonstrating scenarios more similar to "real life" sitiations. As stated in the [introduction chapter](docs/introduction.md) we use the [Tutorial](https://redwoodjs.com/docs/introduction) application as the subject of testing.

Most of the test will use [Jest](https://jestjs.io/) tool, and we will also demonstrate how to use [Wallaby](https://wallabyjs.com/) tool. See also [this](/tools/wallaby.md) article introducing wallaby in the context of RedwoodJS scenario.

Let's also use the description of the JavaScript testing as written by [Kent C. Dodds](https://kentcdodds.com/), well known educator on "everything on software".

> A test is code that throws an error when the actual result of something does not match the expected output. It can get more complicated when you're dealing with code that depends on some state to be set up first (like a component needs to be rendered to the document before you can fire browser events, or there needs to be users in the database). However, it is relatively easy to test "pure functions" like those in our math.js module (functions which will always return the same output for a given input and not change the state of the world around them).
>
>The part that says actual !== expected is called an "assertion." It's a way to say in code that one thing should be a certain value or pass a certain... eh... test :) It could be an assertion that the actual matches a regex, is an array with a certain length, or any number of things. The key is that if our assertion fails, then we throw an error.
