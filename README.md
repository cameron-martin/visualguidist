# visualguidist
Visual regression testing for react-styleguidist

## Usage

Add the following to your styleguidist config

```js
module.exports = {
  context: {
    Qa: 'snapguidist/wrapper'
  }
};
```

Then wrap any examples that you want testing in 
