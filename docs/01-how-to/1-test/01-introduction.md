---
title: "introduction"
sidebar-position: 1
---

# introduction

This introductory chapter to testing RedwoodJS application refers back to the very detailed [initially provided chapter on testing](https://redwoodjs.com/docs/testing). This document presents the `real life` testing scenarios instead of the code segments used so far.

```
const add = (a, b) => {
  return a + b
}
```

together with the test snippet:

```
if (add(1, 1) === 2) {
  console.log('pass')
} else {
  console.error('fail')
}
```
