# @dramaorg/reprehenderit-pariatur-porro

## Install

Do not use it if you can use maps.

```sh
yarn add @dramaorg/reprehenderit-pariatur-porro
```

or if npm is package manager of your choice

```sh
npm install @dramaorg/reprehenderit-pariatur-porro --save
```

## Usage

### I want to create a new object

```js
import box from '@dramaorg/reprehenderit-pariatur-porro';

const trackedObj = box({});
```

### I have an existing object

```js
import box from '@dramaorg/reprehenderit-pariatur-porro';

const myObj = { 
  a: true,
  b: void 0,
};

const trackedObj = box(myObj);
// alternatively if you want to provide a custom orer
const trackedReversedObj = box(myObj, ['b', 'a']);
```

## LICENSE

[Apache License 2.0](https://github.com/dramaorg/reprehenderit-pariatur-porro/blob/master/LICENSE)
