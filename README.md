# @kollorg/saepe-eum

## Install

Do not use it if you can use maps.

```sh
yarn add @kollorg/saepe-eum
```

or if npm is package manager of your choice

```sh
npm install @kollorg/saepe-eum --save
```

## Usage

### I want to create a new object

```js
import box from '@kollorg/saepe-eum';

const trackedObj = box({});
```

### I have an existing object

```js
import box from '@kollorg/saepe-eum';

const myObj = { 
  a: true,
  b: void 0,
};

const trackedObj = box(myObj);
// alternatively if you want to provide a custom orer
const trackedReversedObj = box(myObj, ['b', 'a']);
```

## LICENSE

[Apache License 2.0](https://github.com/kollorg/saepe-eum/blob/master/LICENSE)
